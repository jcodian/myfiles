# myfiles

        JS Files
        https://cdnjs.cloudflare.com/ajax/libs/jquery-easing/1.3/jquery.easing.min.js
        
        
        $('a.smoth-menu').bind('click', function(event){
            var $anchor = $(this);
            var headerH = '30';
            $('html, body').stop().animate({
                scrollTop  : $($anchor.attr('href')).offset().top - headerH + "px"
            }, 1200, 'easeInOutExpo');
            event.preventDefault();
        });
