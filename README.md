##  psf 模块划分

- psf-util
- psf-log
- psf-common
- psf-security
- psf-api-gateway
- psf-xxl-job
- psf-minio
- psf-cloud-parent
- psf-cloud-starter
- psf-mybatis-plus
- psf-generator
- psf-limiting
- psf-txlcn

ALTER TABLE `ioc_wall_chart`.`tb_wall_project`   
  ADD COLUMN `district` VARCHAR(50) DEFAULT ''  NOT NULL   COMMENT '项目所属区划' AFTER `deleted`;