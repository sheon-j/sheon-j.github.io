# sheon-j.github.io

## How to Use

1. **파일 생성**: `docs/` 디렉토리에 `.md` 파일 생성
   - 예: `docs/development/python/basics.md`

2. **YAML Front Matter 작성**:

   ```yaml
   ---
   title: "문서 제목"
   nav_order: 1
   ---
   ```

3. **마크다운 작성**: 일반 마크다운 문법 사용
   - 코드 블록: `rouge` 문법 하이라이팅 지원
   - 다이어그램: `mermaid` 지원

### 네비게이션 구조

- 파일 경로가 자동으로 사이드바 네비게이션에 반영됨
- `nav_order`로 순서 조정 가능
- 폴더 구조로 카테고리 분류 (Guide, Development, Notes 등)

### 참고사항

- 마크다운: `kramdown` 사용
- 문법 하이라이팅: `rouge`
- 마지막 수정 시간 자동 표시
- GitHub Pages에 푸시하면 자동 배포

## References

- [just-the-docs](https://just-the-docs.com/)
- [just-the-docs github](https://github.com/just-the-docs/just-the-docs)
