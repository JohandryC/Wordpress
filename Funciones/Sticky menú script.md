Porción de Script para pasar el botón del plugin para el Sticky menú para el lado derecho y adicional le añade el url al texto.

jQuery(document).ready(function( $ ){	
    $(".njt-nofi-text.njt-nofi-padding-text").insertAfter(".njt-nofi-button.njt-nofi-padding-text");
	$(".njt-nofi-text.njt-nofi-padding-text")
	.css('cursor', 'pointer')
		.on("click", function(){
		  window.open("https://us02web.zoom.us/webinar/register/4416904873167/WN_XVEylJobScqPptN_zkqwJw", "_blank");
		});
});