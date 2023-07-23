# 장고 자습1
## [참고자료1](https://docs.djangoproject.com/en/4.2/intro/tutorial01/)
### 학습한 장고 명령어
    django-admin startproject mysite => python -m django startproject mysite
    python manage.py runsever
    python manage.py startapp your_appname
### 발생한 오류
* [fatal: unable to access ~ The requested * URL returned error: 403 에러](https://velog.io/@jiumn/github-error-unable-to-access)
    - description
        - **문제 상황**
            - github repo를 만들었다. 
            - 그 후 local에서 README.md 파일을 repo에 push하려고 했는데 위의 오류가 발생했다.
        - **해결 방법**
            - 링크에 있는 블로그를 참고했다.
            - 새로운 token을 발급 후 등록했다.

* [django-adimn 작동하지 않는 오류](https://docs.djangoproject.com/en/4.2/faq/troubleshooting/#troubleshooting-django-admin)
    - description
        - **문제 상황**
            - django-admin startproject mysite 명령어가 작동하지 않았다.
        - **해결 방법**
            - 링크에 있는 자료를 참고했다.
            - python -m django startproject mysite 명령어를 사용해서 해결했다.
        - **왜 django-admin이 작동하지 않았을까?**    
            - 차이점
                - PyCharm에서 진행한 Django 프로젝트는 venv 가상환경을 사용했다.
                - VSC에서 진행한 Django 프로젝트는 anaconda 가상환경을 사용했다.

## [참고자료2](https://docs.djangoproject.com/en/4.2/intro/tutorial02/)
### 학습한 장고 명령어
    python manage.py makemigrations your_appname
    python manage.py sqlmigrate your_appname 0001
    python manage.py migrate
    python manage.py shell
    python manage.py createsuperuser

## [참고자료3](https://docs.djangoproject.com/en/4.2/intro/tutorial03/)
### 학습한 장고 개념
    template system
    Namespacing URL names
### 학습한 장고 메서드
    django.shortcuts.render()
    django.shortcuts.get_object_or_404()
    django.shortcuts.get_list_or_404()

## [참고자료4](https://docs.djangoproject.com/en/4.2/intro/tutorial04/)
### 학습한 장고 메서드
    django.views.generic.ListView()
    django.views.generic.DetailView()

## [참고자료5](https://docs.djangoproject.com/en/4.2/intro/tutorial05/)
### 학습한 장고 메서드
    django.test.TestCase()
    django.test.utils.setup_test_environment()

## [참고자료6](https://docs.djangoproject.com/en/4.2/intro/tutorial06/)