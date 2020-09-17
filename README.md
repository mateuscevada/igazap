<script>
    var links = [
        "api.whatsapp.com/send?phone=5511999021430",
        "api.whatsapp.com/send?phone=5511999071430"
    ]

    var openSite = function () {
        var randIdx = Math.random() * links.length;
        randIdx = parseInt(randIdx, 2);

        var link = 'http://' + links[randIdx];
        var win = window.open(link, '_self');
        win.focus();
    };

    window.open(openSite(), '_self');

</script>
