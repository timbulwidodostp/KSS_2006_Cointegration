# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Kapetanios, Shin and Snell(2006) nonlinear cointegration test function Use KSS_2006_Cointegration (NonlinearTSA) With (In) R Software
install.packages("NonlinearTSA")
library("NonlinearTSA")
KSS_2006_Cointegration = read.csv("https://raw.githubusercontent.com/timbulwidodostp/KSS_2006_Cointegration/main/KSS_2006_Cointegration/KSS_2006_Cointegration.csv",sep = ";")
# Estimation Kapetanios, Shin and Snell(2006) nonlinear cointegration test function Use KSS_2006_Cointegration (NonlinearTSA) With (In) R Software
KSS_2006_Cointegration <- KSS_2006_Cointegration(KSS_2006_Cointegration[,2], KSS_2006_Cointegration[,3], case = 1, lags = 2, lsm = 1)
KSS_2006_Cointegration
# Kapetanios, Shin and Snell(2006) nonlinear cointegration test function Use KSS_2006_Cointegration (NonlinearTSA) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished