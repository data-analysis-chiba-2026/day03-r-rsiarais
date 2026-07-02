# DAY 3 HOMEWORK
> #
> # Name: Risa Imai
> 
> # 0. This demonstrates how to save your answers.
> # I've written the answer for you.
> #
> # For example:
> # Calculate the product of 365 and 5.
> # Save your answer to an object called answer_0
> 
> answer_0 <- 365 * 5
> 
> # 1. Let's use R to calculate body mass index (BMI)
> #
> # The formula for BMI is weight divided by the square of height,
> # where weight is in kilograms and height is in meters.
> #
> # Start with the weight and height below, where weight_lb is in pounds
> # and height_ft is in feet.
> #
> # Save your answer in an object called answer_1 and use only
> # R code to make your calculation.
> #
> # HINT: use 1 ft = 0.3048 m
> # HINT: use 1 lb = 0.4536 kg
> 
> weight_lb <- 160
> height_ft <- 6
> 
> # 2. The following code has an error. Fix it by editing the code.
> # (You don't need to save a separate answer for this one, just fix the code.)
> 
> volume_oz <- 130
> volume_ml <- Volume_oz * 29.574
エラー: オブジェクト 'Volume_oz' がありません

> #1
> weight_kg <- weight_lb * 0.453592
> height_m <- height_ft * 0.3048
> BMI <- weight_kg/(height_m^2)
> answer_1 == BMI
エラー: オブジェクト 'answer_1' がありません

> answer_1 <- weight_kg/(height_m^2)
> 
> #2
> volume_ml <- volume_oz * 29.574
> 
> #3
> x <- 2
> y <- 3
> z <- x + y
> x <- 5
> z <- x + y
> 
> answer_3 <- z
> 
> #4
> answer_4 <- sqrt(200)
> 
> #5
> ?seq
> answer_5 <- seq(from=2,to=100,by=2)
> 
> #6
> lgl_vec <- c(TRUE, FALSE, TRUE)
> chr_vec <- c("A","B","C")
> mixed <- c(lgl_vec,chr_vec)
> answer_6 <- typeof(mixed)
> 
> #7
> answer_7 <- letters[seq(from=1,to=26,by=2)]