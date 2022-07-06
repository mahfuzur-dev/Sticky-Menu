# Sticky-Menu
Navbar Sticky menu 


// sticky menu js
$(window).scroll(function(){
    var sticky = $(this).scrollTop()
    if(sticky > 300){
      $('.navbar').addClass('sticki_menu')
    }
    else{
      $('.navbar').removeClass('sticki_menu')
    }
  });
  
  // sticky menu js
