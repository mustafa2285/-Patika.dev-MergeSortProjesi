# Patika.dev Merge Sort Projesi

# [16,21,11,8,12,22] -> Merge Sort

## Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

## step0 =  [16,21,11,8,12,22]

## step1 =  [16,21,11] <> [8,12,22]

## step2 =  [16,21] <> [11] <> [8,12] <> [22]

## step3 =  [16] <> [21] <> [11] <> [8] <> [12] <> [22]

## step4 =  [16,21] <> [11] <> [8,12] <> [22]

## step5 =  [11,16,21] <> [8,12,22]

## step6 =  [8,11,12,16,21,22]

## Big-O gösterimini yazınız.

## [00] => [0] <> [0] 

## 2^x = n => x = logn

## her ayırma ve birleştirme işlemde O(n) geldiği için => O(n logn)
