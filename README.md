# abdullah
abdullah's code
<script>
//
var offset = 68
$(window).on('load scroll', function(){
    
    if( $(window).scrollTop() > offset ){
        $('body').addClass('show')
    }else{
        $('body').removeClass('show')
    }
})
</script>
