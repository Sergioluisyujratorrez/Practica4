![image](https://user-images.githubusercontent.com/65771955/82717873-4cc60380-9c9f-11ea-88e0-72f87055feb6.png)


![image](https://user-images.githubusercontent.com/65771955/82717879-52234e00-9c9f-11ea-9578-1d20eceef193.png)

![image](https://user-images.githubusercontent.com/65771955/82717887-58192f00-9c9f-11ea-90a1-c925478dd459.png)



![image](https://user-images.githubusercontent.com/65771955/82717889-5d767980-9c9f-11ea-820d-67cd6d8f5ccc.png)

***********************************************************************************************************************
/*
Navicat MySQL Data Transfer

Source Server         : SOTFWARE
Source Server Version : 100316
Source Host           : localhost:3306
Source Database       : bd_blog

Target Server Type    : MYSQL
Target Server Version : 100316
File Encoding         : 65001

Date: 2020-05-23 02:21:31
*/

SET FOREIGN_KEY_CHECKS=0;

-- ----------------------------
-- Table structure for salud
-- ----------------------------
DROP TABLE IF EXISTS `salud`;
CREATE TABLE `salud` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `fecha` date DEFAULT NULL,
  `titulo` varchar(255) COLLATE utf8_unicode_ci DEFAULT NULL,
  `contenido` varchar(255) COLLATE utf8_unicode_ci DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=17 DEFAULT CHARSET=utf8 COLLATE=utf8_unicode_ci;

-- ----------------------------
-- Records of salud
-- ----------------------------
INSERT INTO `salud` VALUES ('2', '2020-05-14', 'INGENIERIO DE SISTEMAS', 'La ingeniería de sistemas es una rama interdisciplinaria de la ingeniería que permite estudiar y comprender la realidad, con el propósito de implementar u optimizar sistemas complejos');
INSERT INTO `salud` VALUES ('16', '2020-05-13', 'COMPUTACIONES', 'La informatica, â?? tambien llamada computacion â?? es una ciencia que administra mÃ©todos, tecnicas y procesos con el fin de almacenar, procesar y transmitir informacion y datos en formato digital.             ');

-- ----------------------------
-- Table structure for usuarios
-- ----------------------------
DROP TABLE IF EXISTS `usuarios`;
CREATE TABLE `usuarios` (
  `usuario` varchar(255) COLLATE utf8_unicode_ci NOT NULL,
  `password` varchar(255) COLLATE utf8_unicode_ci DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COLLATE=utf8_unicode_ci;

-- ----------------------------
-- Records of usuarios
-- ----------------------------
INSERT INTO `usuarios` VALUES ('sergio', '123');
SET FOREIGN_KEY_CHECKS=1;
