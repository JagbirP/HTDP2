# HTDP2
HTDP2 Exercises 

;Exercise 1

(define x 3)
(define y 4)

(sqrt (+ (sqr x) (sqr y)))

> 5


;Exercise 2

(define prefix "hello")
(define suffix "world")

(string-append prefix "_" suffix)

>"hello_world"


;Exercise 3

(define str "helloworld")
(define i 5)

(string-append (substring str 0 i)
               (string-append "_" (substring str i)))
              
>"hello_world"


;Exercise 4

(define str "helloworld")
(define i 5)

 (string-append (substring str 0 4)
   (substring str 6))
   
> "helloorld"   
   
   
;Exercise 5

