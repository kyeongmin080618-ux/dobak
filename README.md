# 한 번만 더? — Vercel 배포

정적 웹 게임입니다. 빌드 명령이나 서버 함수가 필요하지 않습니다.

## Vercel에 배포하기

1. `index.html`, `style.css`, `game.js`, `vercel.json`과 이 README를 저장소 최상위에 올립니다.
2. Vercel에서 **Add New → Project**를 선택하고 저장소를 연결합니다.
3. Root Directory는 저장소 기본값(`.`)을 사용합니다.
4. Framework Preset은 **Other**, Build Command는 비워 두고, Output Directory는 `.`으로 설정합니다.
5. **Deploy**를 누르면 공개 웹 주소가 생성됩니다.

또는 저장소를 내려받은 뒤 프로젝트 폴더에서 `vercel --prod`를 실행할 수 있습니다.

게임은 실제 돈이 아닌 가상 게임머니만 사용합니다. 돌아보기 입력 내용은 저장하거나 전송하지 않습니다.

