# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Marginal Effects Estimation for Model Objects Use margins With (In) R Software
install.packages("margins")
library("margins")
margins = read.csv("https://raw.githubusercontent.com/timbulwidodostp/margins/main/margins/margins.csv",sep = ";")
# Estimation Marginal Effects Estimation for Model Objects Use margins With (In) R Software
margins_ <- lm(margins ~ margins_1 + margins_2 + margins_3, data = margins)
margins <- margins(margins_)
margins
summary(margins)
# Marginal Effects Estimation for Model Objects Use margins With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished