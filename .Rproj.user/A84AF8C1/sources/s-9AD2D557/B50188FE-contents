getwd()


# 오칙연산
1+1
a <- 1
a
b <- 2
b
vec01<- c(1,2,3,7)
vec01
vec02 <- c(1:5)
vec02
vec03<- seq(1,5)
vec03
vec04 <- 1:5
vec04
vec05 <- seq(1L,10L, by=2)
vec05
class(vec05)
vec06 <- c("Hello,World!")
vec06
class(vec06)
vec06 <- 1:3
mean(vec06)
class(vec06)
max(x)
x <- 1:5
max(x)
min(x)
x <- c(1,3,5,7)
y <- c(2,3,4,5)
x+y
vec01 + x
xy
x*y
cat("Hello World \n")
mean(x+y)
## 5 + 7 더하기 로직을 구하시오
x <- 5
y <- 7
op <- "+"
eq <- "="
cat(x,op,y,eq,x+y)
### 더하기 로직을 구하시오
plus <- function(x,y){return(x+y)}
plus(3,4)

minous <- function(x,y){return(x-y)}
minous(6,3)

multiple <- function(x,y){return(x*y)}
multiple(125,125)

divid <- function(x,y){return(x%/%y)}
divid(3,3)

remainder <- function(x,y){return(x%%y)}
remainder(3,1)

## if else 구문
op <- "+"
x <- 6
y <- 3
if(op=="+")print(x + y) else
if(op=="-")print(x - y) else
if(op=="*")print(x * y) else
if(op=="/")print(x %/% y) else
if(op=="%")print(x %% y) else
  print("error")

##assignment <- 할당
## brach : 분기문
## loop : 반복문

## if - else 구문:: 함수 만들기 ㅈ
x <- 20
op <- "+"
y <- 3
if(op=="+")cat(x,op,y,"=", x+y)else
if(op=="-")cat(x,op,y,"=", x-y)else
if(op=="*")cat(x,op,y,"=", x*y)else
if(op=="/")cat(x,op,y,"=", x/y)else
if(op=="%")cat(x,op,y,"=", x%%y)else
  print("error")
  

## switch 구문
x <- 20
op <- "+"
y <- 3
switch (
  op,
  "+"=cat(x,op,y,"=", x+y),
  "-"=cat(x,op,y,"=", x-y),
  "*"=cat(x,op,y,"=", x*y),
  "/"=cat(x,op,y,"=", x%/%y),
  "%"=cat(x,op,y,"=", x%%y),
  "error"
)

## if - else 구문 ::함수
calc <- function(x, op, y){
  res <-if(op=="+")cat(x,op,y,"=",x + y) else
  if(op=="-")cat(x,op,y, "=", x - y) else
  if(op=="*")cat(x, op, y,"=", x * y) else
  if(op=="/")cat(x, op, y, "=",x %/% y) else
  if(op=="%")cat(x, op, y, "=",x %% y) else
    print("error")
  return(res)
}
calc(4, "-", 2)

calc <- function(x,op,y)
{res  <-switch (
  op,
  "+"=print(x,op,y,"=", x+y),
  "-"=print(x,op,y,"=", x-y),
  "*"=print(x,op,y,"=", x*y),
  "/"=print(x,op,y,"=", x%/%y),
  "%"=print(x,op,y,"=", x%%y),
  "error"
)return(res)
}
calc(3, "-", 5)

calc <- function(x,op,y){
  res<- if(op=="+")x+y else
    if(op=="-")x-y else
    if(op=="*")x*y else
    if(op=="/")x%/%y else
    if(op=="%")x%%y else
   "error"
  return(cat(x,op,y,"=",res))
}

calc <- function(x,op,y){
  res <-switch (
    op,
    "+"= x+y,
    "-"= x-y,
    "*"= x*y,
    "/"= x%/%y,
    "%"= x%%y,
    "error"
  )
  
  return(cat(x,op,y,"=",res))
  }
calc(4, "+", 5)


##성적표
# kor, eng, math, 총점, 평균
# >결과 grade(80,80,80) 
 sum <- kor + eng + math
   총점  <- cat(총점,sum)
    
    grade <- function(x,y,z){
     sum <- x+y+z
     avg <- sum%/%3
     return(cat(총점,sum,평균,avg))
     }
   grade(70,80,70)
   
#모범답안
grade <- function(kor,eng,math){
  sum <- kor+eng+math
  avg <- sum/3
  return(cat(sum,avg))
  }
grade(10,10,10)

##성적표
#kor, eng, math, 총점, 평균
#grade(80,80,80)
#"총점:sum, 평균:mean"
#if else, switch
# 평균 90이상 A 80이상 B 70이상 C 60 이상 D
# 50이상 E, 그밖이면 F

grade <- function(kor,eng,math){
  sum <- kor+eng+math
  avg <- sum / 3
  return(cat("총점 :",sum ,"평균 :",avg ))
} 