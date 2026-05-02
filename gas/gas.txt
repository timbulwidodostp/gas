# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Estimate generalized autoregressive score (GAS) Model Use gas (gasmodel) With (In) R Software
install.packages("gasmodel")
library("gasmodel")
# Estimate generalized autoregressive score (GAS) Model Use gas (gasmodel) With (In) R Software
gas = read.csv("https://raw.githubusercontent.com/timbulwidodostp/gas/main/gas/gas.csv",sep = ";")
y <- gas$quantity
x <- as.matrix(gas[3:9])
gas <- gas(y = y, x = x, distr = "negbin", regress = "sep")
gas
# Estimate generalized autoregressive score (GAS) Model Use gas (gasmodel) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished