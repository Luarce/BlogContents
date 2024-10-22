### アニメタイトル画像にキャプションをつける

<style>
    @import url("https://raw.githubusercontent.com/Luarce/hatenablog-contents/refs/heads/main/assets/css/hatena-design.css");
</style>

<!-- md -->
<div class="anime_title">
    <img class="anime_image" src="https://raw.githubusercontent.com/Luarce/hatenablog-contents/refs/heads/main/assets/images/anime-reviews/roshidere_title.png" alt="時々ボソッとロシア語でデレる隣のアーリャさん">
    <div class="anime_caption">
    ©Sunsunsun,Momoco/KADOKAWA/Alya-sanPartners
    </div>
</div>

<!-- css -->
<style>
/* アニメタイトル画像にキャプションをつける */
.anime_title {
    position: relative;
    display: inline-block;
}

.anime_image {
    display: block;
}

.anime_caption {
    position: absolute;
    bottom: 0;
    width: 100%;
    padding: 2px;
    background-color: rgba(128, 128, 128, 0.7);
    color: #fff;
    font-size: 13px;
    text-align: center;
}
</style>

#### HTML
```html
<div class="anime_title">
    <img class="anime_image" src="https://raw.githubusercontent.com/Luarce/hatenablog-contents/refs/heads/main/assets/images/anime-reviews/roshidere_title.png" alt="時々ボソッとロシア語でデレる隣のアーリャさん">
    <div class="anime_caption">
    ©Sunsunsun,Momoco/KADOKAWA/Alya-sanPartners
    </div>
</div>
```
#### CSS
```css
.anime_title {
    position: relative;
    display: inline-block;
}

.anime_image {
    display: block;
}

.anime_caption {
    position: absolute;
    bottom: 0;
    width: 100%;
    padding: 2px;
    background-color: rgba(128, 128, 128, 0.7);
    color: #fff;
    font-size: 13px;
    text-align: center;
}
```


### ネタバレ防止
<!-- md -->
<details class="spoiler_details">
    <summary>
        <span style="color: #d32f2f">
        <strong>ED一覧（※ネタバレ注意）</strong></span>
        <u>[クリックで展開]</u>
    </summary>
ネタバレテキスト
</details>

<!-- css -->
<style>
/* ネタバレ防止 */
.spoiler_details {
    background-color: #f0f0f0;
    padding: 15px;
    border-radius: 5px;
    border: 1px solid #ddd;
    color: #333;
    margin-top: 10px;
}
</style>

