# correccionhaskell-tp1
Corrección TP1 Funcional (año bisiesto)

superfieTrangulo :: Float -> Float -> Float superficieTriangulo base altura = (base * altura) / 2.0

potencia :: Int -> Int -> Int potencia base exponente = base ^ exponente

abisiesto :: Int -> Bool aBisiesto año = (año mod 4 == 0 && año mod100 /=0) || año mod 400 == 0
