<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>喜楽多合同会社 | 会社案内</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Hiragino Kaku Gothic ProN', 'メイリオ', sans-serif; }
        body { background-color: #f9f9f9; color: #333; line-height: 1.6; padding: 20px; max-width: 1000px; margin: 0 auto; }
        header { text-align: center; padding: 30px 0; border-bottom: 2px solid #0052cc; margin-bottom: 30px; }
        header h1 { color: #0052cc; font-size: 2.2em; margin-bottom: 10px; }
        header p { color: #666; font-size: 1.1em; }
        section { background: white; border-radius: 8px; padding: 25px; margin-bottom: 25px; box-shadow: 0 2px 8px rgba(0,0,0,0.08); }
        h2 { color: #0052cc; border-left: 4px solid #0052cc; padding-left: 12px; margin-bottom: 20px; }
        .intro p { margin-bottom: 15px; font-size: 1.05em; }
        .business-items { list-style: none; margin-left: 20px; }
        .business-items li { padding: 5px 0; }
        .business-items li:before { content: "✓ "; color: #00a950; font-weight: bold; }
        .image-gallery { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; margin: 20px 0; }
        .image-gallery img { width: 100%; max-width: 300px; height: 200px; object-fit: cover; border-radius: 5px; box-shadow: 0 3px 6px rgba(0,0,0,0.1); border: 1px solid #eee; }
        .map-container { width: 100%; overflow: hidden; padding-top: 56.25%; /* 16:9 Aspect Ratio */ position: relative; }
        .map-container iframe { position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0; }
        .contact { display: flex; flex-wrap: wrap; gap: 20px; justify-content: space-around; align-items: center; }
        .contact-item { flex: 1; min-width: 250px; text-align: center; padding: 20px; border: 1px solid #ddd; border-radius: 8px; }
        .contact-item h3 { margin-bottom: 10px; color: #333; }
        .contact-item a { display: inline-block; margin-top: 10px; padding: 10px 20px; background: #0052cc; color: white; text-decoration: none; border-radius: 5px; font-weight: bold; }
        .contact-item a:hover { background: #003d99; }
        footer { text-align: center; margin-top: 40px; padding: 20px; color: #888; font-size: 0.9em; border-top: 1px solid #eee; }
        @media (max-width: 768px) { .image-gallery { flex-direction: column; align-items: center; } .contact { flex-direction: column; } }
    </style>
</head>
<body>
    <header>
        <h1>喜楽多合同会社</h1>
        <p>日本の産業用電気設備・自動化機器の専門商社</p>
    </header>
    
    <section class="intro">
        <h2>会社案内</h2>
        <p>弊社は、日本のPLC、サーボモーター、センサーをはじめとする電気設備などの商材を取り扱う貿易事業を主たる事業としております。</p>
        <p>また、輸出販売事業が軌道に乗り次第、中国の商材等の輸入販売事業にも順次着手する計画でございます。</p>
    </section>
    
    <section>
        <h2>主な取扱品目</h2>
        <ul class="business-items">
            <li>PLC (プログラマブルロジックコントローラ) および制御システム</li>
            <li>サーボモーター・ステッピングモーター および ドライバ</li>
            <li>各種センサー (光電・近接・圧力・温度など)</li>
            <li>電気配線部品・制御盤機器</li>
            <li>産業用ロボット関連機器</li>
        </ul>
    </section>
    
    <section>
        <h2>事業所イメージ / 取扱製品</h2>
        <div class="image-gallery">
            <!-- 图片1: 店铺外观或办公室形象 -->
            <img src="https://images.unsplash.com/photo-1560179707-f14e90ef3623?w=400&h=300&fit=crop" alt="オフィス外観イメージ">
            <!-- 图片2: PLC/控制柜等产品示例 -->
            <img src="https://images.unsplash.com/photo-1581094794329-c8112a89af12?w-400&h=300&fit=crop" alt="制御盤・PLCイメージ">
            <!-- 图片3: 伺服电机/传感器示例 -->
            <img src="https://images.unsplash.com/photo-1581094794329-c8112a89af12?w=400&h=300&fit=crop" alt="サーボモーター・センサーイメージ">
        </div>
        <p style="text-align:center; margin-top:10px; font-size:0.9em; color:#666;">※ 上記はイメージ画像です。実際の商品・施設とは異なる場合がございます。</p>
    </section>
    
    <section>
        <h2>アクセス</h2>
        <p><strong>所在地：</strong> 〒599-0221大阪府阪南市石田330-1</p>
        <p><strong>最寄り駅：</strong> 阪和線「和泉鳥取駅」より車5分</p>
        <div class="map-container">
            <!-- *** 重要：请替换此处的Google Maps嵌入链接 *** -->
            <!-- 1. 前往 maps.google.co.jp 找到您公司的精确位置。
                 2. 点击“共有” → “地図を埋め込む” → 选择大小 → 复制HTML代码。
                 3. 用复制的整个<iframe>标签替换掉下面这行注释。 -->
            <!-- 示例代码（请替换） -->
            <iframe src="<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>喜楽多合同会社 | 会社案内</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Hiragino Kaku Gothic ProN', 'メイリオ', sans-serif; }
        body { background-color: #f9f9f9; color: #333; line-height: 1.6; padding: 20px; max-width: 1000px; margin: 0 auto; }
        header { text-align: center; padding: 30px 0; border-bottom: 2px solid #0052cc; margin-bottom: 30px; }
        header h1 { color: #0052cc; font-size: 2.2em; margin-bottom: 10px; }
        header p { color: #666; font-size: 1.1em; }
        section { background: white; border-radius: 8px; padding: 25px; margin-bottom: 25px; box-shadow: 0 2px 8px rgba(0,0,0,0.08); }
        h2 { color: #0052cc; border-left: 4px solid #0052cc; padding-left: 12px; margin-bottom: 20px; }
        .intro p { margin-bottom: 15px; font-size: 1.05em; }
        .business-items { list-style: none; margin-left: 20px; }
        .business-items li { padding: 5px 0; }
        .business-items li:before { content: "✓ "; color: #00a950; font-weight: bold; }
        .image-gallery { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; margin: 20px 0; }
        .image-gallery img { width: 100%; max-width: 300px; height: 200px; object-fit: cover; border-radius: 5px; box-shadow: 0 3px 6px rgba(0,0,0,0.1); border: 1px solid #eee; }
        .map-container { width: 100%; overflow: hidden; padding-top: 56.25%; position: relative; }
        .map-container iframe { position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0; }
        .contact { display: flex; flex-wrap: wrap; gap: 20px; justify-content: space-around; align-items: center; }
        .contact-item { flex: 1; min-width: 250px; text-align: center; padding: 20px; border: 1px solid #ddd; border-radius: 8px; }
        .contact-item h3 { margin-bottom: 10px; color: #333; }
        .contact-item a { display: inline-block; margin-top: 10px; padding: 10px 20px; background: #0052cc; color: white; text-decoration: none; border-radius: 5px; font-weight: bold; }
        .contact-item a:hover { background: #003d99; }
        footer { text-align: center; margin-top: 40px; padding: 20px; color: #888; font-size: 0.9em; border-top: 1px solid #eee; }
        @media (max-width: 768px) { .image-gallery { flex-direction: column; align-items: center; } .contact { flex-direction: column; } }
    </style>
</head>
<body>
    <header>
        <h1>喜楽多合同会社</h1>
        <p>日本の産業用電気設備・自動化機器の専門商社</p>
    </header>
    
    <section class="intro">
        <h2>会社案内</h2>
        <p>弊社は、日本のPLC、サーボモーター、センサーをはじめとする電気設備などの商材を取り扱う貿易事業を主たる事業としております。</p>
        <p>また、輸出販売事業が軌道に乗り次第、中国の商材等の輸入販売事業にも順次着手する計画でございます。</p>
    </section>
    
    <section>
        <h2>主な取扱品目</h2>
        <ul class="business-items">
            <li>PLC (プログラマブルロジックコントローラ) および制御システム</li>
            <li>サーボモーター・ステッピングモーター および ドライバ</li>
            <li>各種センサー (光電・近接・圧力・温度など)</li>
            <li>電気配線部品・制御盤機器</li>
            <li>産業用ロボット関連機器</li>
        </ul>
    </section>
    
    <section>
        <h2>事業所イメージ / 取扱製品</h2>
        <div class="image-gallery">
            <img src="https://github.com/jingzhuksatl-arch/images/commit/996322ace3a47447a4da1cefbfcd449a0215fb8c#diff-c184b1682d41570533a2eebbb71ba3a6073928e79c303b65f9bbb7860e8a2cd0" alt="オフィス外観イメージ">
            <img src="https://github.com/jingzhuksatl-arch/images/commit/996322ace3a47447a4da1cefbfcd449a0215fb8c#diff-a3f8473f32a51add02c229ef4dd7eda62b7c0efc7db31ef82d5da99f6d6ac97a" alt="制御盤・PLCイメージ">
            <img src="https://github.com/jingzhuksatl-arch/images/commit/996322ace3a47447a4da1cefbfcd449a0215fb8c#diff-9599ce00baaf8066253898df08f1c171b4f6e6ae04b6eea9452a78a2e887d043" alt="サーボモーター・センサーイメージ">
        </div>
        <p style="text-align:center; margin-top:10px; font-size:0.9em; color:#666;">※ 上記はイメージ画像です。実際の商品・施設とは異なる場合がございます。</p>
    </section>
    
    <section>
        <h2>アクセス</h2>
        <p><strong>所在地：</strong> 〒599-0221 大阪府阪南市石田330-1</p>
        <p><strong>最寄り駅：</strong> 阪和線「和泉鳥取駅」より車5分</p>
        <div class="map-container">
            <iframe src="https://www.google.com/maps/embed?pb=!1m26!1m12!1m3!1d26355.763200575195!2d135.2261581532601!3d34.33850437519958!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m11!3e6!4m3!3m2!1d34.3286036!2d135.2564736!4m5!1s0x6000b6de7982b779%3A0x26b0c3970bd7230d!2zMzMwLTEgSXNoaWRhLCBIYW5uYW4sIE9zYWthIDU5OS0wMjIx5pel5pys!3m2!1d34.3466296!2d135.2411928!5e0!3m2!1szh-CN!2sjp!4v1781714118115!5m2!1szh-CN!2sjp" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
    </section>
    
    <section>
        <h2>お問い合わせ</h2>
        <div class="contact">
            <div class="contact-item">
                <h3>📞 電話</h3>
                <p>090-3590-5888 (代表)</p>
            </div>
            <div class="contact-item">
                <h3>✉️ メール</h3>
                <p>jingzhu@ks-atl.com</p>
            </div>
            <div class="contact-item">
                <h3>📱 スマートフォンで経路案内</h3>
                <a href="https://www.google.com/maps/dir/?api=1&destination=大阪府阪南市石田330-1" target="_blank">Google マップで開く</a>
            </div>
        </div>
    </section>
    
    <footer>
        <p>© 2026 喜楽多合同会社. All Rights Reserved.</p>
    </footer>
</body>
</html>
