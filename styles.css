<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>MAKAHA项目物资管理</title>
<style>
:root{--primary:#1a73e8;--primary-d:#0d47a1;--bg:#f4f6f9;--text:#202124;--sub:#5f6368;}
*{margin:0;padding:0;box-sizing:border-box;}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI','PingFang SC','Hiragino Sans GB',sans-serif;background:var(--bg);color:var(--text);}
.wrap{max-width:460px;margin:0 auto;min-height:100vh;display:flex;flex-direction:column;}
.hero{background:linear-gradient(135deg,var(--primary),var(--primary-d));color:#fff;padding:36px 22px 30px;text-align:center;}
.hero .logo{width:74px;height:74px;border-radius:18px;background:rgba(255,255,255,.16);display:inline-flex;align-items:center;justify-content:center;margin-bottom:14px;box-shadow:0 6px 18px rgba(0,0,0,.18);}
.hero .logo img{width:46px;height:46px;display:block;}
.hero h1{font-size:22px;font-weight:700;letter-spacing:1px;}
.hero p{font-size:13px;opacity:.92;margin-top:6px;}
.body{padding:20px 18px 28px;flex:1;}
.card{background:#fff;border-radius:14px;padding:16px;box-shadow:0 2px 10px rgba(0,0,0,.06);margin-bottom:14px;border:1px solid #eef0f3;}
.card h2{font-size:15px;margin-bottom:10px;display:flex;align-items:center;gap:6px;}
.desc{font-size:13.5px;line-height:1.75;color:var(--sub);}
.desc b{color:var(--text);}
.feats{display:grid;grid-template-columns:1fr 1fr;gap:10px;}
.feat{background:#f7f9fc;border-radius:10px;padding:12px 8px;text-align:center;}
.feat .ic{font-size:24px;}
.feat .t{font-size:13px;font-weight:600;margin-top:4px;}
.feat .d{font-size:11px;color:var(--sub);margin-top:2px;}
.steps{counter-reset:s;list-style:none;}
.steps li{position:relative;padding:9px 0 9px 34px;font-size:13.5px;color:var(--text);line-height:1.55;border-bottom:1px dashed #eee;}
.steps li:last-child{border-bottom:none;}
.steps li::before{counter-increment:s;content:counter(s);position:absolute;left:0;top:9px;width:22px;height:22px;background:var(--primary);color:#fff;border-radius:50%;font-size:12px;display:flex;align-items:center;justify-content:center;font-weight:700;}
.qr{text-align:center;}
.qr img{border:1px solid #e3e6ea;border-radius:12px;padding:10px;background:#fff;width:210px;height:210px;}
.qr .hint{font-size:12px;color:var(--sub);margin-top:10px;}
.btn{display:block;width:100%;text-align:center;background:var(--primary);color:#fff;padding:15px;border-radius:13px;font-size:16px;font-weight:600;text-decoration:none;box-shadow:0 4px 14px rgba(26,115,232,.35);margin-top:14px;}
.btn:active{transform:scale(.98);}
.foot{text-align:center;font-size:11.5px;color:#9aa0a6;padding:14px;line-height:1.6;}
</style>
<script src="https://beacon.cdn.qq.com/sdk/4.5.9/beacon_web.min.js"></script>
<script>
(function(){
  try{
    var beacon=new BeaconAction({
      appkey:'0WEB06U85YBSLJNL',
      versionCode:'1.0.0',
      channelID:'share',
      delay:1000,
      sessionDuration:30*60*1000,
      isOversea:false,
      needReportRqdEvent:false
    });
    beacon.onDirectUserAction('preview_page_view',{
      'url':location.href,
      'referrer':document.referrer,
      'title':document.title,
      'sandbox_id':'044e7754beb6415788c9c38c7dc64eea'
    });
  }catch(e){}
})();
</script></head>
<body>
<div class="wrap">
  <div class="hero">
    <div class="logo"><img src="./icon-192.png" alt="logo"></div>
    <h1>MAKAHA项目物资管理</h1>
    <p>物资入库 · 领用登记 · 库存台账</p>
  </div>
  <div class="body">
    <div class="card">
      <h2>📋 项目说明</h2>
      <p class="desc">本工具用于 MAKAHA 钻探队物资的<b>入库登记</b>、<b>领用登记</b>与<b>库存管理</b>。团队成员可随时用手机记录，库存自动汇总，低库存自动预警，方便现场物资管控与对账。</p>
    </div>
    <div class="card">
      <h2>✨ 主要功能</h2>
      <div class="feats">
        <div class="feat"><div class="ic">📥</div><div class="t">物资入库</div><div class="d">登记入库明细</div></div>
        <div class="feat"><div class="ic">📤</div><div class="t">物资领用</div><div class="d">登记领用去向</div></div>
        <div class="feat"><div class="ic">📊</div><div class="t">库存预警</div><div class="d">低库存红色提醒</div></div>
        <div class="feat"><div class="ic">👥</div><div class="t">多人协作</div><div class="d">就地记录·导出同步</div></div>
      </div>
    </div>
    <div class="card">
      <h2>🚀 使用步骤</h2>
      <ol class="steps">
        <li>打开应用，底部切换「物资入库 / 物资领用」</li>
        <li>点「＋ 新增」填写时间、物资、数量等信息</li>
        <li>顶部库存总览自动汇总，低库存红色预警</li>
        <li>点右上角「⇅ 同步数据」导出 JSON 发给队友，队友导入即同步</li>
      </ol>
    </div>
    <div class="card qr">
      <h2 style="justify-content:center">📱 扫码进入应用</h2>
      <img src="./qrcode.png" alt="应用二维码">
      <div class="hint">手机扫码直接打开，或点击下方按钮</div>
      <a class="btn" href="./app.html">打开应用 →</a>
    </div>
    <div class="foot">数据保存在本机浏览器，离线可用<br>通过导出 / 导入 JSON 实现多人同步</div>
  </div>
</div>
</body>
</html>
