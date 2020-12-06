# carrito-compras
es un simple y sencillo carrito de compras creado con php y mysqli







nombre de la base de datos `carrito_compras`
CREATE TABLE IF NOT EXISTS `carrito` (
 `id` int(11) NOT NULL,
 `nombre` varchar(255) NOT NULL,
 `imagen` varchar(255) NOT NULL,
 `precio` double() NOT NULL,
 `mensaje` varchar(255) NOT NULL
) ENGINE=MyISAM AUTO_INCREMENT=4 DEFAULT CHARSET=latin1;
 
 
 INSERT INTO `productos` (`id`, `name`, `image`, `price`) VALUES
(1, 'Monitor LED UHD 24&amp;amp;quot; U24E590D', 'http://images.samsung.com/is/image/samsung/es_LU24E590DS-EN_001_Front_black?$DT-Gallery$', 200.00),
(2, 'Monitor LED Curvo 27&amp;amp;quot; C27F591FDU', 'http://images.samsung.com/is/image/samsung/es_LC27F591FDUXEN_001_Front_white?$DT-Gallery$', 588.00),
(3, 'Galaxi note 7', 'http://www.samsung.com/es/consumer/mobile-devices/smartphones/galaxy-note/galaxy-note7/smart-switch/images/apps_smart-switch_banner_img.png', 499.00);
 nota: ESTOS SON ALGUNOS DE SUS DATOS ALMACENADOS
