* 가상환경 설치
  1. 웹사이트를 담기 위해 만들어 둔 폴더로 이동
  2. ```python -m venv {{가상환경 이름}}``` 입력

* 가상환경 실행(window)
  - ```source 가상환경폴더/Scripts/activate``` 입력
  - Error1 (powerShell 보안 이슈): ```이 시스템에서 스크립트를 실행할 수 없으므로 ...파일을 로드할 수 없습니다 + CategoryInfo: 보안오류```
    + 해결방법: 터미널에서 ```Set-ExecutionPolicyRemoteSigned -Scope Process``` 입력(일시적으로 스크립트 실행을 허용함)
