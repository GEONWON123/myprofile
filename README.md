# 이건원 자기소개 웹사이트 (Django 과제)

## 소개
Django를 사용해 만든 간단한 자기소개 웹사이트입니다.  
취미, 특기, 한국 축구 기사 링크, 연락처 정보를 포함하고 있습니다.

---

## 프로젝트 구조
```
myprofile/
├── manage.py
├── main/
│   ├── views.py
│   ├── templates/
│   │   └── main/
│   │       └── index.html
├── myprofile/
│   ├── settings.py
│   ├── urls.py
```

---

## 앱 실행 방법

1. GitHub 저장소 클론
    ```bash
    git clone https://github.com/GEONWON123/myprofile.git
    cd myprofile
    ```

2. 가상환경 생성 (선택)
    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

3. Django 설치
    ```bash
    pip install django
    ```

4. 서버 실행
    ```bash
    python manage.py runserver
    ```

5. 브라우저에서 접속  
   주소창에 입력: `http://127.0.0.1:8000`

---

## 정보

- 이름: 이건원  
- 취미: 축구경기 관람  
- 특기: 러닝  
- 연락처: 010-1234-5678

---

## 기타
이 프로젝트는 Django 수업 과제를 위해 제작되었습니다.
