DB file

DROP DATABASE if exists epharmacy_db;
CREATE DATABASE epharmacy_db;
USE epharmacy_db;

CREATE TABLE MEDICINE  (
	MEDICINE_ID INT AUTO_INCREMENT,
	MEDICINE_NAME VARCHAR(100) NOT NULL,
	MANUFACTURER VARCHAR(50) NOT NULL,
    PRICE INT NOT NULL,
    DISCOUNT_PERCENT INT NOT NULL,
    MANUFACTURING_DATE date NOT NULL,
    EXPIRY_DATE date NOT NULL,
    CATEGORY VARCHAR(50) NOT NULL,
    QUANTITY INT NOT NULL,
    CONSTRAINT MEDICINE_PK primary key ( MEDICINE_ID )
);

INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1011, 'Augmentin 625 Duo Tablet','Glaxo SmithKline Pharmaceuticals Ltd', 240, 15,'2022/02/20', '2022/02/25', 'Allopathy',20);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1012, 'Allegra-M Tablet','Sanofi India Ltd',340, 15,'2021/08/22', '2026/08/24', 'Allopathy',15);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1013, 'Azee 500 Tablet','Cipla Ltd', 200, 20,'2022/08/22','2024/11/08', 'Allopathy',10);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1014, 'Ketosteril Tablet','Fresenius Kabi India Pvt Ltd', 324, 25, '2020/08/22', '2023/02/02', 'Allopathy',20);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1015, 'Seroflo 250 Inhaler', 'Cipla Ltd', 450, 16, '2020/08/20', '2024/06/28', 'Allopathy',4);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1016, 'Heptral 400mg Tablet', 'Abbott', 450, 20, '2022/08/22', '2025/12/12', 'Allopathy',19);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1017, 'Foracort Inhaler 200','Cipla Ltd',450,30,'2021/06/22','2025/09/01','Allopathy',23);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1018, 'Azithral 500 Tablet','Alembic Pharmaceuticals Ltd',150,21,'2021/08/22','2025/11/21','Allopathy',11);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1019, 'Lipaglyn Tablet','Zydus Cadila',250,21,'2020/08/22','2024/01/11','Allopathy',10);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1020, 'Letroz Tablet','Sun Pharmaceutical Industries Ltd',150,20,'2020/08/22','2023/11/21','Allopathy',20);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1021, 'LizolID 600 Tablet','Integrace Pvt Ltd',180,14,'2020/08/22','2025/09/11','Allopathy',3);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1022, 'Lyrica 75mg Capsule','Pfizer Ltd',550,20,'2022/08/22','2023/04/01','Allopathy',5);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1023, 'L-Hist Mont Tablet','Alkem Laboratories Ltd',120,20,'2020/08/22','2026/12/07','Allopathy',10);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1024, 'PAN 40 Tablet','Alkem Laboratories Ltd',150,24,'2021/08/22','2024/07/24','Allopathy',11);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1025, 'Primolut-N Tablet','Zydus Cadila',100,25,'2023/01/01','2024/08/01','Allopathy',20);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1026, 'PlacIDa Tablet','Mankind Pharma Ltd',150,24,'2021/08/22','2022/07/01','Allopathy',11);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1027, 'Pantop-D SR Capsule','Aristo Pharmaceuticals Pvt Ltd',150,20,'2023/01/01', '2026/08/01','Allopathy',1);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1028, 'PregabID NT Tablet','Intas Pharmaceuticals Ltd',200,20,'2023/01/01','2025/09/11','Allopathy',21);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1029, 'Progynova 2mg Tablet','Bayer Zydus Pharma Pvt Ltd',110,22,'2023/01/01','2025/07/21','Allopathy',4);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE,EXPIRY_DATE,CATEGORY,QUANTITY) VALUES (1030, 'Pregaba-M 75 Capsule','Torrent Pharmaceuticals Ltd',150,30,'2023/01/01','2025/01/31','Allopathy', 3);

INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1031, 'Orthoron Paste 60 ml','Natural Remedies Pvt. Ltd.',450,30,'2022/08/12','2025/09/11','Veterinary',234);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1032, 'Bites Milk Flavour 75 gm','Natural Remedies Pvt. Ltd.',350,24,'2023/01/03','2025/09/11','Veterinary',88);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1033, 'Himalaya Erina EP Powder','Himalaya Wellness Company',190,24,'2023/01/03','2025/09/11','Veterinary',78);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1034, 'Himalaya Himcal Pet','Himalaya Wellness Company',750,26,'2022/01/04','2024/09/10','Veterinary',67);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1035, 'Mobility Bites','Natural Remedies Pvt. Ltd.',180,12,'2022/08/07','2024/06/09','Veterinary',88);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1036, 'Nefrotec DS Vet Tablets','Himalaya Wellness Company',340,15,'2022/06/09','2025/07/12','Veterinary',67);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1037, 'Whiskas Adult','Mars International India Pvt Ltd',150,20,'2023/01/03','2026/09/08','Veterinary',56);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1038, 'Wiggles Barkstix Dogs','Sixth Sense Retail Private Limited',450,40,'2023/01/03','2024/09/10','Veterinary',89);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1039, 'Wiggles Puppy Food',' Sixth Sense Retail Private Limited',1750,50,'2023/01/03','2025/06/11','Veterinary',98);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1040, 'Anti Hairfall Shampoo','Natural Remedies Pvt. Ltd.',155,17,'2022/08/04','2024/08/12','Veterinary',56);

INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1041, 'Sugar Free Gold Powder','Mankind Pharma Ltd',350,40,'2023/07/01','2025/05/11','Diabetes',67);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1042, 'Pro360 Diabetic Powder',' Sixth Sense Retail Private Limited',280,30,'2022/05/06','2025/10/21','Diabetes',68);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1043, 'Dr Morepen Test Strips','Himalaya Wellness Company',150,40,'2022/05/01','2025/01/13','Diabetes',87);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1044, 'Accu Instant Glucometer','Mankind Pharma Ltd',200,50,'2023/11/01','2025/12/01','Diabetes',89);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1045, 'Accu Active Test Strip','Himalaya Wellness Company',260,30,'2023/07/11','2025/07/08','Diabetes',90);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1046, 'Garlic Oil 500mg capsules','Natural Remedies Pvt. Ltd.',210,15,'2022/07/04','2024/08/01','Diabetes',98);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1047, 'Kapiva Karela Jamun Juice','Mankind Pharma Ltd',240,12,'2023/07/18','2025/02/26','Diabetes',75);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1048, 'Dprotin Chocolate Powder','Natural Remedies Pvt. Ltd.',310,25,'2022/08/01','2024/07/09','Diabetes',83);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1049, 'Nestle Opti Powder',' Sixth Sense Retail Private Limited',260,30,'2023/05/15','2025/01/27','Diabetes',72);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1050, 'Onetouch Select Test Strip','Mankind Pharma Ltd',150,20,'2022/12/15','2025/11/22','Diabetes',86);

INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1051, 'Dettol Antiseptic Liquid','Alkem Laboratories Ltd',250,14,'2022/08/24','2024/07/24','Covid Essentials',87);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1052, 'Fastup Effervesent Tablet','Mankind Pharma Ltd',170,25,'2022/07/22','2022/07/14','Covid Essentials',88);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1053, 'Healthvit Omega3 Fish Oil','Himalaya Wellness Company',180,13,'2022/02/13','2024/02/14','Covid Essentials',78);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1054, 'Newnikpulse Oximeter','Alkem Laboratories Ltd',210,14,'2022/04/18','2024/07/14','Covid Essentials',79);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1055, 'Omron Compressor Nebulizer','Alkem Laboratories Ltd',230,23,'2022/09/19','2024/03/24','Covid Essentials',80);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1056, 'Piramal Tri Activ N95','Natural Remedies Pvt. Ltd.',150,14,'2022/09/09','2025/06/24','Covid Essentials',90);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1057, 'Surgical Hand Disinfectant','Alkem Laboratories Ltd',150,15,'2022/07/21','2024/07/27','Covid Essentials',92);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1058, 'Univen Powder','Mankind Pharma Ltd',200,13,'2022/05/22','2024/07/24','Covid Essentials',97);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1059, 'Vaporizer Steam Inhaler','Natural Remedies Pvt. Ltd.',250,14,'2022/01/21','2024/06/24','Covid Essentials',94);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1060, 'Stevia Dry Leaves','Himalaya Wellness Company',190,15,'2023/07/22','2025/07/24','Covid Essentials',95);

INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1061, 'Dabur Pudin Capsule','Himalaya Wellness Company',170,14,'2022/07/04','2024/08/24','Ayush',85);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1062, 'Liv52 Tablet','Natural Remedies Pvt. Ltd.',190,13,'2023/01/02','2024/02/14','Ayush',87);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1063, 'Dabur Chyawanprash','Alkem Laboratories Ltd',210,15,'2022/02/05','2025/07/24','Ayush',86);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1064, 'Dabur Gold Capsule','Mankind Pharma Ltd',150,20,'2022/08/09','2025/08/24','Ayush',88);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1065, 'Dabur Pudinhara Liquid','Natural Remedies Pvt. Ltd.',240,16,'2022/09/17','2024/05/12','Ayush',89);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1066, 'Zandubalm','Alkem Laboratories Ltd',140,15,'2022/02/24','2025/03/24','Ayush',97);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1067, 'Dabur Hajmola Tablets','Mankind Pharma Ltd',250,13,'2023/07/14','2025/07/17','Ayush',95);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1068, 'Orthoherb Tablet','Mars International India Pvt Ltd',260,15,'2022/06/13','2024/06/04','Ayush',96);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1069, 'Prosteez Tablet','Alkem Laboratories Ltd',160,15,'2023/11/24','2025/10/24','Ayush',92);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1070, 'Dabur Stresscom Capsules','Himalaya Wellness Company',150,14,'2023/07/19','2025/07/19','Ayush',94);

INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1071, 'Fortivirone Drops','Alkem Laboratories Ltd',330,40,'2022/05/24','2024/07/24','Homeopathy',97);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1072, 'Allen A84 Lipoma Drops','Mars International India Pvt Ltd',450,50,'2022/06/24','2024/07/23','Homeopathy',89);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1073, 'Sbl Scalptone Tablet','Natural Remedies Pvt. Ltd.',430,14,'2022/05/20','2024/06/22','Homeopathy',88);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1074, 'Sbl Vertefine Drops','Alkem Laboratories Ltd',210,14,'2022/05/12','2024/07/24','Homeopathy',87);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1075, 'Inhallergol Drops','Natural Remedies Pvt. Ltd.',250,14,'2022/05/24','2024/12/24','Homeopathy',78);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1076, 'Aloevera Bathing Soap','Alkem Laboratories Ltd',150,13,'2022/05/27','2024/08/24','Homeopathy',78);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1077, 'Allen Derma Plus Cream','Mars International India Pvt Ltd',180,14,'2022/12/12','2024/07/24','Homeopathy',96);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1078, 'Blood Urea Creatinin Drops','Himalaya Wellness Company',410,14,'2022/05/24','2024/07/24','Homeopathy',79);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1079, 'Wheezal Anti Snoring Drops','Alkem Laboratories Ltd',400,25,'2022/05/24','2025/06/24','Homeopathy',80);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1080, 'SBL Forenza','Himalaya Wellness Company',380,24,'2022/12/04','2024/12/24','Homeopathy',88);

INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1081, 'Revital Woman Tablet','Natural Remedies Pvt. Ltd.',210,15,'2022/06/21','2024/05/24','Fitness',81);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1082, 'Baconil Tts20 Patch','Himalaya Wellness Company',240,15,'2022/05/24','2024/07/22','Fitness',83);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1083, 'Dprotin Chocolate Powder','Alkem Laboratories Ltd',250,15,'2022/07/14','2024/12/24','Fitness',85);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1084, 'Nicotex Chew Gum','Natural Remedies Pvt. Ltd.',220,15,'2022/07/12','2024/07/11','Fitness',89);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1085, 'Nestle Vanilla Flavour','Natural Remedies Pvt. Ltd.',170,15,'2022/11/11','2024/11/22','Fitness',87);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1086, 'Horlicks Powder Malt','Mars International India Pvt Ltd',190,15,'2022/07/09','2024/07/17','Fitness',88);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1087, 'Garlic Pearls Capsule','Alkem Laboratories Ltd',160,30,'2022/05/24','2025/07/24','Fitness',80);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1088, 'Protinex Powder','Mars International India Pvt Ltd',350,20,'2023/07/24','2025/07/24','Fitness',86);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1089, 'Cadbury Bournvita','Himalaya Wellness Company',450,25,'2022/07/21','2024/12/22','Fitness',82);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1090, 'Hepapro Mixed Fruit Powder','Himalaya Wellness Company',440,40,'2022/06/24','2024/07/14','Fitness',84);

INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1091, 'Nestle Cerelac Powder','Himalaya Wellness Company',156,14,'2022/07/24','2024/07/24','Mom & Baby',97);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1092, 'Whisper Sanitary Pads','Alkem Laboratories Ltd',180,14,'2022/08/25','2025/08/25','Mom & Baby',98);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1093, 'Woodwards Gripe Water','Alkem Laboratories Ltd',210,15,'2022/09/25','2024/05/24','Mom & Baby',90);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1094, 'Cetaphil Baby Daily Lotion','Himalaya Wellness Company',210,14,'2022/05/22','2024/07/24','Mom & Baby',92);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1095, 'Johnsons Buds','Alkem Laboratories Ltd',170,13,'2022/11/11','2025/07/27','Mom & Baby',91);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1096, 'Pampers Baby Dry Pants','Natural Remedies Pvt. Ltd.',155,13,'2022/04/21','2024/12/24','Mom & Baby',88);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1097, 'Himalaya Baby Shampoo','Alkem Laboratories Ltd',150,14,'2022/03/22','2024/02/24','Mom & Baby', 76);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1098, 'Himalaya Baby Powder','Alkem Laboratories Ltd',180,14,'2022/05/21','2024/07/29','Mom & Baby',89);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1099, 'Aptamil Infant Powder','Natural Remedies Pvt. Ltd.',150,13,'2022/11/22','2024/07/01','Mom & Baby',81);
INSERT INTO MEDICINE(MEDICINE_ID, MEDICINE_NAME, MANUFACTURER, PRICE,DISCOUNT_PERCENT,MANUFACTURING_DATE, EXPIRY_DATE,category,QUANTITY) VALUES (1100, 'Himalaya Baby Cream','Alkem Laboratories Ltd',170,14,'2022/07/12','2024/09/23','Mom & Baby',72);

SELECT * FROM MEDICINE;

commit;


CREATE TABLE PRIME_PLANS(
	PLAN_ID INT PRIMARY KEY,
	PLAN_NAME VARCHAR(20),
	PLAN_DESCRIPTION VARCHAR(255)
);

CREATE TABLE CUSTOMER (
	CUSTOMER_ID INT AUTO_INCREMENT,
	CUSTOMER_NAME VARCHAR(30) NOT NULL,
	CUSTOMER_EMAIL_ID VARCHAR(30) NOT NULL,
	CONTACT_NUMBER VARCHAR(10) NOT NULL,
	GENDER VARCHAR(10),
	DATE_OF_BIRTH VARCHAR(15),
	PASSWORD VARCHAR(70) NOT NULL,
	PLAN_ID INT,
	PLAN_EXPIRY_DATE DATE,
	CONSTRAINT EPHARMACY_CUST_PK primary key ( CUSTOMER_ID ),
	CONSTRAINT EPHARMACY_CUST_PLAN__FK FOREIGN KEY (PLAN_ID) REFERENCES PRIME_PLANS (PLAN_ID)
);
CREATE TABLE CUSTOMER_ADDRESS (
	ADDRESS_ID INT AUTO_INCREMENT,
	CUSTOMER_ID INT,
	ADDRESS_NAME VARCHAR(15) ,
	ADDRESS_LINE1 VARCHAR(30) ,
	ADDRESS_LINE2 VARCHAR(30) ,
	AREA VARCHAR(20) ,
	CITY VARCHAR(17) ,
	STATE VARCHAR(20) ,
	PINCODE INT ,
	CONSTRAINT EPHARMACY_CUST_ADDR_PK primary key ( ADDRESS_ID ),
	CONSTRAINT EPHARMACY_CUST_ADDR__FK FOREIGN KEY (CUSTOMER_ID) REFERENCES CUSTOMER (CUSTOMER_ID)
);



INSERT INTO PRIME_PLANS VALUES (1, 'MONTHLY', 'Get 5% off on every order');  
INSERT INTO PRIME_PLANS VALUES (2, 'QUARTERLY', 'Get 10% off on every order');
INSERT INTO PRIME_PLANS VALUES (3, 'YEARLY', 'Get 15% off on every order');


INSERT INTO CUSTOMER_ADDRESS VALUES (1,101,'Home','40A, Prestige Apartments','Gunjur Mohalla','Anand Vihar','Noida','Uttar Pradesh',110029);
INSERT INTO CUSTOMER_ADDRESS VALUES (2,101,'Work','Reliance Industrial Area','Diamond City','Vasant Vihar','Delhi','Delhi',110029);
INSERT INTO CUSTOMER_ADDRESS VALUES (3,103,'Home','A2/1, Indira Colonies','Lalvani Nagar','Baner','Pune','Maharashtra',411037);
INSERT INTO CUSTOMER_ADDRESS VALUES (4,103,'Work','A705, AjayDeep Complex','Lalvani nagar','Kothrud','Pune','Maharashtra',411037);
INSERT INTO CUSTOMER_ADDRESS VALUES (5,105,'Home','309, Leo Janani Apartments','Lakshmikanth nagar','Rajouri Garden','Delhi','Delhi',110027);
INSERT INTO CUSTOMER_ADDRESS VALUES (6,104,'Home','187, Sumeru Nilaya','6th Cross Road','Madegowda Circle','Mysore','Karnataka',570016);


SELECT * FROM PRIME_PLANS;
SELECT * FROM CUSTOMER;
SELECT * FROM CUSTOMER_ADDRESS;


commit;



CREATE TABLE CART (
   CART_ID INT AUTO_INCREMENT PRIMARY KEY,
    CUSTOMER_EMAIL_ID VARCHAR(30) NOT NULL
);


SELECT * FROM CART;

commit;

CREATE TABLE PRODUCT(
PRODUCT_ID  INT PRIMARY KEY AUTO_INCREMENT,
CART_ID INT,
MEDICINE_ID INT NOT NULL,
QUANTITY INT,
CONSTRAINT CART_FK FOREIGN KEY (CART_ID) REFERENCES CART (CART_ID));
Select * from product;

commit;



CREATE TABLE ORDERS(
	ORDER_ID BIGINT PRIMARY KEY AUTO_INCREMENT,
	PAYMENT_ID INT,
	MRP_TOTAL DECIMAL(7,2),
	DISCOUNT_PERCENT INT,
	DISCOUNTED_TOTAL DECIMAL(7,2),
	DELIVERY_DATE DATETIME,
	CUSTOMER_EMAIL_ID VARCHAR(30) NOT NULL,
	ORDER_STATUS ENUM('PROCESSING','CONFIRMED','CANCELLED','COMPLETED'),
	ORDER_DATE DATETIME,
	CANCEL_REASON VARCHAR(500),
	DELIVERY_ADDRESS_ID INT,
	CARD_ID VARCHAR(16)
);

CREATE TABLE ORDERED_MEDICINE(
	ORDERED_MEDICINE_ID INT PRIMARY KEY AUTO_INCREMENT,
	ORDER_ID BIGINT,
	ORDERED_QUANTITY INT,
	MEDICINE_ID INT,
	CONSTRAINT order_FK FOREIGN KEY (ORDER_ID) REFERENCES ORDERS (ORDER_ID)
);
SELECT * FROM ORDERED_MEDICINE;


commit;


CREATE TABLE CARD(
	CARD_ID VARCHAR(16) PRIMARY KEY, 
	NAME_ON_CARD VARCHAR(50),
	CVV VARCHAR(70),
	CARD_TYPE ENUM('DEBIT_CARD','CREDIT_CARD'),
	EXPIRY_DATE VARCHAR(20),
	CUSTOMER_EMAIL_ID VARCHAR(30) NOT NULL
);

CREATE TABLE PAYMENT(
	PAYMENT_ID INT PRIMARY KEY AUTO_INCREMENT,
	PAYMENT_TIME DATETIME,
	AMOUNT DECIMAL(10,2),
      CUSTOMER_EMAIL_ID VARCHAR(30) NOT NULL,
	CARD_ID VARCHAR(16) REFERENCES CARD(CARD_ID)
	
);


commit;

