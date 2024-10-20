書き出し

[:contents]

### 見出し

本文

<div style="text-align: center"><strong>おわり</strong></div>

<!-- 記事タイトル：アニメ感想（2024夏） -->

<!-- サムネイル：https://raw.githubusercontent.com/Luarce/hatenablog-contents/refs/heads/main/assets/images/anime-reviews/makeine_title.png -->

<!-- css -->
<style>
@import url("../../assets/css/hatena-design.css");
</style>

<!-- js -->
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script>
$(function() {
    var contentsText = "目次";
    var closeText = "[ 閉じる ]";
    var openText = "[ 表示 ]";

    var $contents = $(".table-of-contents");
    var $li = $contents.find("li");

    $contents.prepend(
        '<span class="contents">' + contentsText + '</span>' +
        '<span class="switch">' + closeText + '</span>'
    );

    var $switch = $contents.find(".switch");

    $switch.on("click", function() {
        var isHidden = $li.is(":hidden");
        $li.toggle(400);
        $switch.text(isHidden ? closeText : openText);
    });
});
</script>