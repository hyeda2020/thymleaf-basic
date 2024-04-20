# thymleaf-basic
리포지토리 설명 : 인프런 김영한님의 강의 '스프링 MVC 2편 - 백엔드 웹 개발 핵심 기술' thymleaf 기본 파트 스터디 정리  

# 타임리프 소개
공식 사이트: https://www.thymeleaf.org/  
공식 메뉴얼 - 기본 기능: https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html  
공식 메뉴얼 - 스프링 통합: https://www.thymeleaf.org/doc/tutorials/3.0/thymeleafspring.html  

# 타임리프 특징
- 서버 사이드 HTML 렌더링 (SSR)  
- 네츄럴 템플릿  
- 스프링 통합 지원  
  
# 서버 사이드 HTML 렌더링 (SSR)
타임리프는 백엔드 서버에서 HTML을 동적으로 렌더링 하는 용도로 사용  

# 네츄럴 템플릿
타임리프는 순수 HTML을 최대한 유지하는 특징이 있으며,  
타임리프로 작성한 파일은 HTML을 유지하기 때문에 웹 브라우저에서 파일을 직접 열어도 내용을 확인할 수 있고,  
서버를 통해 뷰 템플릿을 거치면 동적으로 변경된 결과를 확인할 수 있음.  
  
이렇게 순수 HTML을 그대로 유지하면서 뷰 템플릿도 사용할 수 있는 타임리프의 특징을  
네츄럴 템플릿(natural templates)이라 함.

# 스프링 통합 지원
타임리프는 스프링과 자연스럽게 통합되고, 스프링의 다양한 기능을 편리하게 사용할 수 있게 지원함.
