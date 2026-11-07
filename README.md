# 옥비디오 · OkVideo

ASRock DeskMini X600 / AMD Ryzen 5 8600G용 미디어 플레이어 OS 배포 저장소입니다. LibreELEC와 Kodi를 기반으로 개인 영상·음원 라이브러리를 관리합니다.

## 다운로드

[현재 배포본: 0.4.0-preview.2](https://github.com/okdaejang-art/okvideo-releases/releases/tag/v0.4.0-preview.2)

[Releases](https://github.com/okdaejang-art/okvideo-releases/releases)에서 버전별 설치 이미지, 업데이트 파일, 소스 코드와 검증 문서를 제공합니다. Preview는 시험 배포 버전입니다.

- 새 SSD 설치: `.img.gz`를 USB에 기록하고 설치 메뉴를 이용합니다. 선택한 설치 대상 SSD의 데이터가 지워집니다.
- 기존 0.3 버전: `-update.tar`를 기기의 `Update` 공유 폴더에 복사한 뒤 재부팅합니다.
- 자동 업데이트 지원 버전: **홈 → 설정 → 옥비디오 업데이트**. 다운로드·검증·설정 백업 후 재부팅해 설치합니다.

0.4.0-preview.2부터 새 버전이 있으면 홈 오른쪽 위에 **업데이트 있음 · 설치**가 표시됩니다. 부팅 후 유휴 상태에서 확인하고 이후 6시간마다 확인합니다. 재생 중에는 확인을 미루며, 설치 파일은 사용자가 버튼을 선택할 때 다운로드합니다.

자동 업데이트 안내는 `updates-preview` 릴리스의 서명된 `latest.json`으로 제공합니다. 버전별 설치 파일은 별도의 `v…` 릴리스에 보관합니다. 옥자막 프로젝트와는 독립적으로 버전과 업데이트를 관리합니다.

## 범위와 개인정보

개인 NAS 계정, SubDL API 키, 영상·음원은 배포 파일에 포함하지 않습니다. SubDL 연결은 사용자가 선택합니다. 재생 기능과 장비별 HDMI/HDR·오디오 호환성의 검증 범위는 해당 버전의 `VALIDATION` 문서를 확인하세요.

## 소스와 라이선스

릴리스에 별도로 첨부한 `OkVideo-<버전>-source.zip`에는 옥비디오 변경 코드, 빌드 스크립트, 테스트와 `LICENSES` 문서가 있습니다. 기반 LibreELEC·Kodi 및 포함 구성요소는 각각의 오픈소스 라이선스를 따릅니다. GitHub가 자동으로 표시하는 `Source code (zip)`은 이 배포 저장소의 문서 사본입니다. 옥비디오 구현 코드는 이름이 `OkVideo-`로 시작하는 소스 ZIP을 받으세요.

사용한 기반 버전과 소스 링크는 빌드 매니페스트와 소스 아카이브에서 확인할 수 있습니다.
