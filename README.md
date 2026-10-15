# 희망장례봉사단 홈페이지

HTML/CSS로 만든 정적 소개 사이트입니다. 별도 설치·빌드·서버 비용이 필요하지 않습니다. 외부 Google Fonts가 차단되면 기기 기본 글꼴로 표시됩니다.

## GitHub Pages 게시

1. GitHub에서 공개 저장소 `hopefuneral`을 만듭니다.
2. 이 폴더의 `index.html`, `style.css`, `flower.svg`, `.nojekyll`, `README.md`를 저장소 최상위에 올립니다. 폴더 자체를 중첩 업로드하지 않습니다.
3. 저장소 Settings → Pages → Build and deployment에서 Deploy from a branch를 선택합니다.
4. Branch는 `main`, 폴더는 `/ (root)`로 지정하고 Save를 누릅니다.
5. 배포가 끝나면 Pages 설정에 실제 공개 주소가 표시됩니다. 일반적인 주소는 `https://계정명.github.io/hopefuneral/`입니다.

## 별도 도메인 연결

GitHub Pages 주소는 무료로 제공됩니다. 별도 무료 서브도메인을 이용하려면 해당 제공자가 GitHub Pages 연결에 필요한 DNS 레코드 설정을 지원해야 합니다. 주소를 확보한 뒤 Pages의 Custom domain과 도메인 제공자의 DNS를 함께 설정합니다. 아직 도메인을 정하지 않아 CNAME 파일은 넣지 않았습니다.

## 내용 수정

- 문구·이메일·단장 인사말: `index.html`
- 색상·간격·모바일 화면: `style.css`
- 로고: `flower.svg` (이 초안용 꽃 심볼)

원본: https://sites.google.com/view/hopefuneral

원본의 단체 소개와 인사말을 바탕으로 문장을 정리했습니다. 활동 실적·계좌·전화번호를 임의로 추가하지 않았습니다. 미확인 통계, 세제 혜택과 후원자별 예우 조건은 옮기지 않았습니다. 후원은 공개된 이메일로 문의하도록 연결했습니다. FAQ와 참여 안내는 사이트 구성을 위해 정리한 초안이므로 단체 운영자가 실제 운영 방식에 맞게 확인할 수 있습니다.

현재 폴더 제작과 GitHub 게시 상태는 별개입니다. 실제 게시 여부는 GitHub 저장소와 Pages 배포 결과로 확인하세요.
