---
title: 'Hero ImagesをAIを利用して生成しました。'
date: '2023-10-17'
lastmod: '2023-10-17'
tags: ['AI', '画像生成', 'ヒーローイメージ']
draft: false
summary: '最近の技術進歩により、AIを活用してヒーローイメージの生成を試みました。その過程と結果を共有します。'
images: ['/static/images/projects/ai_hero_image.png']
authors: ['jsakai']
---

## AIを利用したヒーローイメージの生成

近年、AIの進化は目覚ましく、様々な分野での応用が進められています。
特に画像生成技術は大きな進歩を遂げ、リアルタイムでの生成や編集が可能になっています。

今回、「Jyugon Corp」の企業サイトで使用するヒーローイメージの生成をAI技術を活用して試みました。その過程で使用したツールや、生成されたイメージの品質、そして実際の使用感などをシェアいたします。

### 使用したAI技術


- **ChatGPT**: OpenAIによって開発された最先端の言語モデルで、高度なテキスト生成や対話能力を持っています。この技術を活用して、ヒーローイメージのコンセプトやデザインのガイドラインを整理しました。

- **Midjourny**: こちらの技術も高度な画像生成や編集に関連する能力を持っています。ChatGPTで整理したガイドラインを基に、Midjournyを使って実際の画像を生成しました。


### 生成プロセス
## 1.ChatGPT

**1-1. アイディアの整理**: 企業情報やブランドの背景をもとにヒーローイメージのアイディアを出してもらいます。

> **ChatGPTからの回答抜粋**:
   > - ジュゴンの海中イメージ
   > - テクノロジーと自然の融合
   > - グローバルコミュニティの象徴
   > - 静寂と調和のビジュアル

**1-2. 画質設定の確認**: 生成するヒーローイメージのサイズや画質の設定を整理します。
> **ChatGPTからの回答抜粋**:
>
> ### サイズ
>
> - **デスクトップ:** 通常、1920x1080ピクセルや1440x900ピクセルといったサイズが使用されます。ただし、レスポンシブデザインを心掛けて異なるデバイスでの表示を考慮することが重要です。
> - **モバイル:** モバイルデバイス向けには、360x640ピクセルや375x667ピクセルといったサイズが一般的です。
> - **タブレット:** 768x1024ピクセルや800x1280ピクセルといったサイズが推奨されます。
>
> ### 画質
>
> - **DPI:** ウェブ用の画像では、通常72 DPI（ドット・パー・インチ）を使用します。ただし、高品質のレンダリングを目指す場合は、300 DPIを選ぶこともあります。
> - **ファイル形式:** JPEG や PNG 形式が一般的です。JPEG は高圧縮率でファイルサイズを小さく保てるため、ウェブ用途に適しています。PNG は透明性を保持できる点で優れています。
> - **圧縮:** 適切なバランスを保つために、画像を圧縮することをお勧めします。画質を落としすぎないように注意しながら、ページの読み込み速度を速く保つことが重要です。
>
> ### 追加のヒント
>
> - **アスペクト比:** オリジナルのアスペクト比を保持することで、画像の歪みを防げます。
> - **レスポンシブデザイン:** 異なるデバイスで適切に表示されるように、レスポンシブデザインを採用することをお勧めします。
> - **SEO:** 画像のSEOを最適化するために、適切なALTテキストを使用することを忘れずに。

**1-3. プロンプトの提案**: 画像生成用のプロンプト案を出してもらいます。

> **ChatGPTからの回答抜粋**:
>
>Create a hero image that embodies the harmonious blend of technology and nature for the Jyugon company. The image should depict a serene sea environment with elements of technology subtly integrated. Picture a gentle dugong gracefully swimming in a vibrant underwater landscape that is infused with elements of technology - imagine fiber optic seaweeds, or soft coral formations resembling high-tech structures. The background should portray a beautiful sunset by the sea, incorporating light blue, light pink, and white gradient tones, representing the company's brand color (#22A8B6). 


## 2.Midjourny

**2-1. 画像生成**: 画像生成を繰り返し理想の画像を目指します。


![Tech-inspired seascape with a central dugong in deep teal.](image1.png)
>プロンプト:A high-resolution hero image for a company website, with a size of 1920x1080 pixels and an aspect ratio of 16:9, bright and engaging, technology, dugong, ocean, #22A8B6 A deep teal color, evoking a sense of security and professionalism --v 5.1


![Tech-ocean blend with dugong in bright deep teal, 8k resolution.](image2.png)
>プロンプト:technology, dugong, ocean, #22A8B6 A deep teal color, bright and engaging, evoking a sense of security and professionalism, 8k resolution 16:9, --v 5.1

思うように生成できなかったので、[Midjourney showcase](https://www.midjourney.com/showcase/recent/)を見てインスピレーションを受ける。


![Woman on a beach in chrome reflections and flat art style.](image3.png)
>プロンプト:a painting of woman walking alone on the beach, in the style of chrome reflections, , flat figuration, uhd image, pictorial dreams, full body, strip painting --ar 16:9 --v 5.1

![8k cartoon programmer with laptop and dugong, blue sky backdrop](image4.png)
>プロンプト:8k beauty programar holding laptop, show small duogong duogong face from the ocean, Created a cartoon illustrated poster with ocean background, vast blue sky, soft pixel colors, studio lighting, flat illustrations, minimalist lines, ultra-high quality, ultra-high definition, 8k, vivid strokes --ar 16:9 --v 5.1


Midjournyの設定を変更し、生成を続けます。
![Generated design from Midjourney](image16.png)


![8k illustration: figure with laptop against ocean and sky.](image5.png)
>プロンプト:8k beauty holding laptop. Created a cartoon illustrated poster with ocean background, vast blue sky, soft pixel colors, studio lighting, flat illustrations, minimalist lines, ultra-high quality, ultra-high definition, 8k, vivid strokes --ar 16:9 --niji 5

画像の方向性を再考するために[10 Top Website Hero Images and Best Practices to Create Your Own](https://colibriwp.com/blog/hero-websites/)を読みました。
画像生成を繰り返します。

![Girl with computer against dark San Francisco, candid style.](image6.png)
>プロンプト:girl with computer, dark city front, san francisco, in style of candid portraiture, studyblr, adafruit, sensory experience, grid formation, website, soft focus lens , visual remix style, sabatier filter, innovative innovative page design, anni albers--ar 16:9 --v 5.2

![Elegant Japanese IT engineer programming on a laptop with another screen showing code, lit softly.](image7.png)
>プロンプト:A beautiful Japanese female IT engineer, as stunning as a celebrity, programming an application on a laptop. Another screen is displaying lines of programming code. Lighting: The scene is illuminated by a soft, ambient light that evenly spreads across the engineer's face and the surrounding workspace. The lighting creates a modern and sleek atmosphere, highlighting the engineer's elegance and technical expertise. The illustration captures the IT engineer's poise and intelligence, as she focuses on programming the application. The additional screen displaying lines of code adds depth and complexity to the artwork, symbolizing the engineer's proficiency in software development. Reference: Real - life coding environments, laptops, and renowned individuals known for their beauty and talent --ar 16:9 --v 5.2 

![Beautiful Japanese IT engineer coding on a laptop, soft ambient lighting.](image8.png)
>プロンプト:A beautiful Japanese female IT engineer, as stunning as a celebrity, programming an application on a laptop. Another screen is displaying lines of programming code. Lighting: The scene is illuminated by a soft, ambient light that evenly spreads across the engineer's face and the surrounding workspace. --ar 16:9 --niji 5

![Japanese female IT engineer programming, second screen with code, softly illuminated.](image9.png)
>プロンプト:A beautiful Japanese female IT engineer, as stunning as a celebrity, programming an application on a laptop. Another screen is displaying lines of programming code. Lighting: The scene is illuminated by a soft, ambient light that evenly spreads across the engineer's face and the surrounding workspace. --ar 16:9 --niji 5

![Businessman's hand touching global network connections against sunset, abstract tech imagery.](image10.png)
>プロンプト:Hand of businessman touching circle global network connection and data exchanges on sunset background, Business networking with customer, Science, Innovation, Communication and technology hands touching network with data ring, in the style of lens flare, shaped canvas, abstract landscape, spherical sculptures, selective focus, human-canvas integration white hand touching digital globe in blue sky, in the style of human-canvas integration, light purple and orange --ar 16:7 --niji 5 

気になった画像を基に再生成するため、Seedを取得します。
Seedは、Add reaction、Envelopの絵文字をクリックで取得できます。

![Generated design from Seed.](image17.png)

![Japanese IT engineer with laptop, code on background screen, softly lit. ](image11.png)
>プロンプト:A beautiful Japanese female IT engineer, as stunning as a celebrity, programming an application on a laptop. Another screen is displaying lines of programming code. Lighting: The scene is illuminated by a soft, ambient light that evenly spreads across the engineer's face and the surrounding workspace.
seed 1591934983

人物像のポージングバリエーションをChatGPTに聞き、プロンプトに反映させます。

ここでMidjournyはアスペクト比16:7が非対応ということに気づきました。
このアスペクト比で生成すると上下に黒いボーダーが入ってしまいます。
対応しているアスペクト比3:2で生成し直します。

![Smiling Japanese IT engineer holding laptop, soft ambient lit scene with background code.](image12.png)
>プロンプト:A beautiful Japanese female IT engineer, looking like a celebrity, stands smiling and holding a laptop computer. Lines of programming code are displayed on a screen in the background. Lighting: This scene is lit by soft ambient light that spreads evenly across the engineer's face and surrounding workspace. --ar 3:2 --seed 1591934983 --niji 5


![Joyful Japanese IT engineer celebrating project completion, soft light with background code](image13.png)
>プロンプト:A beautiful Japanese female IT engineer, she is really happy bacause she finished her progject. Lines of programming code are displayed on a screen in the background. Lighting: This scene is lit by soft ambient light that spreads evenly across the engineer's face and surrounding workspace. --ar 3:2 --seed 1591934983 --niji 5

良さそうな画像をハイスケール。
完成です。

![High-resolution image of a generated design](image15.png)


### 結果と感想

ChatGPTとMidjournyを組み合わせることで、独特かつ高品質なヒーローイメージの生成を実現しました。
ChatGPTの生成したプロンプトは完璧ではありませんでしたが、Midjournyの画像生成プロセスでの人物のポージングやバリエーションのアイディア提案として非常に役立ちました。

Midjournyは画像生成AIとしての高い性能を持っています。
設定を最適化して、その可能性を最大限に引き出すことをおすすめします。
理想的なイメージを得たい場合、Seedを活用するとさらに理想に近いイメージを具体化できるでしょう。

プロンプトの構築はやや手間がかかるかもしれませんが、画像編集のステップは格段に迅速化し、効率的な作業が実現しました。

「Alamoa」ブログでは、最新の技術や知識を継続して取り入れ、より質の高いコンテンツをお届けする予定です。お楽しみに。