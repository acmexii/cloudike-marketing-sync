# Cloudike Marketing Sync

클라우다이크 홈페이지의 Git·PR 변경을 확인하고 마케팅 팀 승인 후 소개서와 안내 영상을 최신화하는 스킬입니다.

## 설치

이 저장소의 `skills/cloudike-marketing-sync` 폴더를 사용하는 도구의 skills 경로에 설치합니다.

함께 필요한 스킬:
- [Cloudike Service Video](https://github.com/acmexii/skill-cloudike-service-video): 실제 화면 녹화·마우스 연출·ElevenLabs 설정. `cloudike-service-video`를 이 스킬과 같은 skills 폴더 아래에 설치합니다.
- [MSASchool Purple](https://github.com/acmexii/skill-slide-msaschool): `artifact-template-msaschool-purple` 템플릿 스킬과 자산을 설치합니다.
- 실행 환경의 Presentations, PDF, Google Drive 스킬 및 연결 도구가 필요합니다.

ElevenLabs API 키는 실행 환경에서 별도로 설정합니다. 키·개인 실행 상태는 저장소에 포함하지 않습니다.

## 실행

`cloudike-marketing-sync 스킬을 실행해서 Git·PR 변경을 확인하고 마케팅 팀 승인용 변경안을 보여줘.`

홈페이지: https://acmexii.github.io/cloudikehome/  
대상 저장소: https://github.com/acmexii/cloudikehome

- 홈페이지 전체 콘텐츠의 PR·커밋 Diff 분석
- 변경이 없으면 “변경 된 사항이 없습니다.”로 종료
- 대상 문서·페이지·변경/추가 내용을 먼저 제시하고 명시적 승인 후 실행
- MSASchool 스타일 PPTX·PDF 생성 또는 갱신, Drive 기존 파일 업데이트
- 실제 브라우저 조작 녹화와 지정 ElevenLabs 음성 사용
- 서비스 소개서 PPTX 1개와 동일 최종본의 PDF 1개, 총 2개 생성
- 홈페이지 소개자료 링크는 위 PDF에 직접 연결
- 문서 2개 완성·검수 → 담당자에게 제시 → 명시적 확인 후 영상 제작 착수
- 최종 MP4와 제작 원본은 프로젝트 폴더에만 저장하며 Drive·홈페이지에 게시하지 않음

공식 Cloudike 로고는 스킬 `assets/`에 포함되어 있으며 출처 기록을 함께 제공합니다. 해당 로고의 권리는 원 권리자에게 있습니다.
