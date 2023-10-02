# MyBatis-Sample2

下記記事をパクった。

MyBatisのSQL文をXMLファイルに配置してみた   
https://www.purin-it.com/spring-boot-mybatis-xml

-- USER_DATAテーブルの作成   
  CREATE TABLE "TEST"."USER_DATA"  (
  	"ID" NUMBER(6,0) NOT NULL ENABLE,  
	"NAME" VARCHAR2(40 BYTE) NOT NULL ENABLE,  
	"BIRTH_YEAR" NUMBER(4,0) NOT NULL ENABLE,  
	"BIRTH_MONTH" NUMBER(2,0) NOT NULL ENABLE,  
	"BIRTH_DAY" NUMBER(2,0) NOT NULL ENABLE,  
	"SEX" CHAR(1 BYTE) NOT NULL ENABLE,  
	 PRIMARY KEY ("ID")  );
