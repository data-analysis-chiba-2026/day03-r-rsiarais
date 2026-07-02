
# DAY 3 HOMEWORK
#
# Name: Risa Imai

#1
weight_kg <- weight_lb * 0.4536
height_m <- height_ft * 0.3048
BMI <- weight_kg/(height_m^2)
answer_1 <- weight_kg/(height_m^2)
#2
volume_ml <- volume_oz * 29.574
#3
x <- 2
y <- 3
z <- x + y
x <- 5
z <- x + y
answer_3 <- z
#4
answer_4 <- sqrt(200)
#5
?seq
answer_5 <- seq(from=2,to=100,by=2)
#6
lgl_vec <- c(TRUE, FALSE, TRUE)
chr_vec <- c("A","B","C")
mixed <- c(lgl_vec,chr_vec)
answer_6 <- typeof(mixed)
#7
answer_7 <- letters[seq(from=1,to=26,by=2)]