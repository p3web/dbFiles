CREATE TABLE users (
  ID int(11) NOT NULL,
  UserName varchar(50) NOT NULL COMMENT 'نام کاربری',
  Pasword varchar(50) DEFAULT NULL,
  Email varchar(50) DEFAULT NULL,
  Mobile varchar(50) DEFAULT NULL,
  Avatar varchar(50) DEFAULT NULL,
  LastLogin varchar(50) DEFAULT NULL,
  FailedCount varchar(50) DEFAULT NULL,
  LastModify varchar(50) DEFAULT NULL,
  isDelete bit(1) DEFAULT NULL,
  CreateBy varchar(50) DEFAULT NULL,
  CreationDate timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
  PRIMARY KEY (ID)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
