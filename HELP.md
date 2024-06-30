## Poetry 파이썬 패키지 관리자 

```shell
# Install poetry (powershell)
(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python - 


poetry new [패키지명]: 새로운 프로젝트를 생성합니다.

poetry install: pyproject.toml 파일에 명시된 파이썬 패키지들을 설치합니다.

poetry add [패키지명]: 패키지를 프로젝트에 추가합니다.

poetry remove [패키지명]: 패키지를 프로젝트에서 제거합니다.

poetry update [패키지명]: 패키지를 최신 버전으로 업데이트합니다.

poetry show: 설치된 패키지와 그 의존성들을 보여줍니다.

poetry build: 패키지를 빌드하여 배포 준비를 합니다.

poetry publish --build: 패키지를 PyPI에 배포합니다.

poetry run [명령어]: poetry 환경에서 명령어를 실행합니다.

poetry shell: poetry 가상환경 쉘을 실행합니다.
```