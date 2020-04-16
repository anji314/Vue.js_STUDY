# Vue.js_STUDY
Vue.js 공부 하기      
실습한 내용을 올릴 예정    
book : Doit Vue.js 입문


## [1] Vue.js의 단위
#### 1. 인스턴스   -> [인스턴스 실습](https://github.com/anji314/Vue.js_STUDY/blob/master/vue_instance.html)
```
  - 화면을 개발하기 위해 필수적으로 생성해야하는 기본 단위. 
```
##### 1.1 인스턴스 옵션 속성 
```
  * el : 뷰로 만든 화면이 그려지는 시작점을 의미.
  * data
  * template : 화면에 표시할 HTML,CSS 등의 마크업 요소를 정의하는 속성.
  * methods : 전반적인 이벤트 화면 동작과 관련된 화면 로직 제어 메서드를 정의하는 속성
  * created : 뷰 인스턴스가 생성되자마자 실행할 로직을 정의할 수 있는 속성.(뷰 인스턴스 라이프 사이클)
```
##### 1.2 인스턴스가 화면에 적용되는 과정
```
1. 뷰 라이브러리 파일 로딩
2. 인스턴스 객체 생성(옵션 속성 포함)
3. 특정 화면 요소에 인스턴스를 붙임
4. 인스턴스 내용이 화면 요소로 변환
5. 변환된 화면 요소를 사용자가 최종 확인
```
##### 1.3 뷰 라이프 사이클  -> [라이프 사이클 실습](https://github.com/anji314/Vue.js_STUDY/blob/master/vue_lifecycle.html)
```
1. beforeCreate : 인스턴스 생성 후 가장 먼저 실행되는 라이프 사이클 단계
2. created : 
3. beforeMount
4. mounted
5. beforeUpdate
6. updated
7. beforeDestroy
8. destroyed
```
 
  
#### 2. 컴포넌트
