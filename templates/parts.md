# HTML&CSSテンプレ集

### アニメタイトル画像にキャプションをつける_md
<div class="anime_title">
    <img class="anime_image" src="https://raw.githubusercontent.com/Luarce/hatenablog-contents/refs/heads/main/assets/images/anime-reviews/roshidere_title.png" alt="時々ボソッとロシア語でデレる隣のアーリャさん">
    <div class="anime_caption">
    ©Sunsunsun,Momoco/KADOKAWA/Alya-sanPartners
    </div>
</div>

<style>
/* アニメタイトル画像にキャプションをつける_CSS */
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
