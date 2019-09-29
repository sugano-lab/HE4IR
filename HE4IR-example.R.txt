dat<-matrix(
  c(29021,6910,5103,36526,46503,39762,2018,50,50,66,187,15,
    92162,9510,2117,10310,4505,1037,76165,8331,3235,10785,6030,1628,
    27979,3873,1682,5565,3722,1309),ncol = 5)
colnames(dat)<-c("Senmon","Kanri","Jimu","Hanbai","Etc")
rownames(dat)<-c("Bunkei","Etc","Nougaku","Kyouiku","Rikou","Hoken")
mosaicplot(dat,las=2,main="Social Division of Labor 2018")
