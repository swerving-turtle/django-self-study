# 장고 자습
## [참고자료](https://docs.djangoproject.com/en/4.2/intro/tutorial01/)
### 발생한 오류
* [fatal: unable to access ~ The requested * URL returned error: 403 에러](https://velog.io/@jiumn/github-error-unable-to-access)
    - description
        - 문제 상황
            - github repo를 만들었다. 
            - 그 후 local에서 README.md 파일을 repo에 push하려고 했는데 위의 오류가 발생했다.
        - 해결 방법
            - 링크에 있는 블로그를 참고했다.
            - 새로운 token을 발급 후 등록했다.

* [django-adimn 작동하지 않는 오류](https://docs.djangoproject.com/en/4.2/faq/troubleshooting/#troubleshooting-django-admin)
    - description
        - 문제 상황
            - django-admin startproject mysite 명령어가 작동하지 않았다.
        - 해결 방법
            - 링크에 있는 자료를 참고했다.
            - python -m django startproject mysite 명령어를 사용해서 해결했다.
        - 의문점    
            - PyCharm에서는 django-admin이 작동했는데 VSC에서는 동작하지 않았다.
                - PyCharm에서 진행한 Django 프로젝트는 venv 가상환경을 사용했다.
                - VSC에서 진행한 Django 프로젝트는 anaconda 가상환경을 사용했다.

### 실행결과 분석