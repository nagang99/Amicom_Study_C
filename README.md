# Amicom C 스터디 연습장

- 아미콤 C 스터디 전용 레포지토리입니다.
- 매 주차마다 학습 내용과 실습 내용을 README 파일과 각자의 C 파일에 자유롭게 작성합니다.
- 정해진 작성 형식은 없습니다.

## 1주차 배운 내용
```
#include <stdio.h> 

int main(){

    printf("%s", "Total days in Year\n");
    printf("%d\n",365);
    printf("%s\n", "Circumference rate");
    printf("%lf\n",3.1415926535);


    int a, b;
    scanf("%d %d", &a,&b);
    printf("%d %d",a,b);

    return 0;
}
```

## 2주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 3주차 배운 내용
```
#include <stdio.h>

int count_num(int arr){
    do{
        if(arr % 10 == 3 || arr % 10 == 6 ||arr % 10 == 9){
            return 0;
        }
        arr = arr / 10; 
    }while(arr != 0);
    return 1;
}

int main(){
    int a, b;
    int arr[110];
    int count;
   
    while(1){
        printf("입력 : ");
        scanf("%d %d", &a,&b);
        if (a<=99 && a>=1 && b<=99 && b>=1){
            break;
        }
    }

    for(int i = 0 ; i < (b-a+1) ; i++){
        arr[i] = a + i;
        if(arr[i] % 3 == 0 || count_num(arr[i]) == 0){
            count ++;
            continue;
        }
    }

    printf("출력 : %d", count);
    
    return 0;
}

```

## 4주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 5주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 6주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 7주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 8주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 9주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 10주차 배운 내용
- 이곳에 작성하시면 됩니다.
