# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Bayesian multilevel quantile regression Use bqmm With (In) R Software
install.packages("bqmm")
library("bqmm")
# Estimate Bayesian multilevel quantile regression Use bqmm With (In) R Software
bqmm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/bqmm/main/bqmm/bqmm.csv",sep = ";")
bqmm_1 <- bqmm(bqmm ~ bqmm_1 + (1 | bqmm_3), data = bqmm, tau = 0.5, chains = 1, iter = 300, refresh = 0, seed = 1)
bqmm_2 <- bqmm(bqmm ~ bqmm_1 + (1 | bqmm_2), data = bqmm, tau = 0.5, chains = 1, iter = 300, refresh = 0, seed = 1)
summary(bqmm_1)
summary(bqmm_2)
# Bayesian multilevel quantile regression Use bqmm With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished