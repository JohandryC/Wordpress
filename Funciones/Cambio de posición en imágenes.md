
Script para cambio de posición de imágenes en resolución mobile menor a 767px de ancho.

/*Cambio de imagenes por cambio de resoluciones*/
jQuery(document).ready(function( $ ){
	let resolucion = $(window).width();
	if (resolucion <= 767) {
       $(".page-id-23130 #panel-23130-5-0-0").appendTo($(".page-id-23130 #panel-23130-5-1-1"));
		$(".page-id-23130 #panel-23130-7-0-0").appendTo($(".page-id-23130 #panel-23130-7-1-1"));
		$(".page-id-23158 #panel-23158-5-0-0").appendTo($(".page-id-23158 #panel-23158-5-1-1"));
		$(".page-id-23158 #panel-23158-7-0-0").appendTo($(".page-id-23158 #panel-23158-7-1-1"));
		$(".page-id-23083 #panel-23083-3-0-0").appendTo($(".page-id-23083 #panel-23083-3-1-1"));
		$(".page-id-23083 #panel-23083-5-0-0").appendTo($(".page-id-23083 #panel-23083-5-1-1"));
    }
	$($(window).width()).change(function(){
	if (resolucion <= 767) {
       $(".page-id-23130 #panel-23130-5-0-0").appendTo($(".page-id-23130 #panel-23130-5-1-1"));
		$(".page-id-23130 #panel-23130-7-0-0").appendTo($(".page-id-23130 #panel-23130-7-1-1"));
		$(".page-id-23158 #panel-23158-5-0-0").appendTo($(".page-id-23158 #panel-23158-5-1-1"));
		$(".page-id-23158 #panel-23158-7-0-0").appendTo($(".page-id-23158 #panel-23158-7-1-1"));
		$(".page-id-23083 #panel-23083-3-0-0").appendTo($(".page-id-23083 #panel-23083-3-1-1"));
		$(".page-id-23083 #panel-23083-5-0-0").appendTo($(".page-id-23083 #panel-23083-5-1-1"));
    }else{
		$(".page-id-23130 #panel-23130-5-0-0").appendTo($(".page-id-23130 #panel-23130-5-0"));
		$(".page-id-23130 #panel-23130-7-0-0").appendTo($(".page-id-23130 #panel-23130-7-0"));
		$(".page-id-23158 #panel-23158-5-0-0").appendTo($(".page-id-23158 #panel-23158-5-0"));
		$(".page-id-23158 #panel-23158-7-0-0").appendTo($(".page-id-23158 #panel-23158-7-0"));
		$(".page-id-23083 #panel-23083-3-0-0").appendTo($(".page-id-23083 #panel-23083-3-0"));
		$(".page-id-23083 #panel-23083-5-0-0").appendTo($(".page-id-23083 #panel-23083-5-0"));
	}
	});
});