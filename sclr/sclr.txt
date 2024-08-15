# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Maximum likelihood estimation of the scaled logit (logistic) regression model parameters Use sclr With (In) R Software
install.packages("sclr")
library("sclr")
sclr = read.csv("https://raw.githubusercontent.com/timbulwidodostp/sclr/main/sclr/sclr.csv",sep = ";")
# Estimation Maximum likelihood estimation of the scaled logit (logistic) regression model parameters Use sclr With (In) R Software
sclr <- sclr(status ~ logHI, sclr)
summary(sclr)
# Maximum likelihood estimation of the scaled logit (logistic) regression model parameters Use sclr With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished