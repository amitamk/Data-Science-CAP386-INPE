# Script para a solução do Ex2 da Lista Week 2

baltimore <- c(3.47,	3.02, 3.93,	3.00,	3.89,	3.43,	3.85,	3.74,	3.98,	3.16,	3.12,	3.35)

names(baltimore) <- c("Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec")

baltimoreInMM <- baltimore * 25.4

baltimoreInMM

infoBaltimore <- summary(baltimoreInMM)

infoBaltimore[c(1,4,6)]