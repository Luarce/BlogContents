[:contents]

### 見出し3



<!-- css関連 -->
<style>
@import url("../../assets/css/hatena-design.css");
</style>

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

