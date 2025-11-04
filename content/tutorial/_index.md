# post 섹션
mkdir -p content/post
cat > content/post/_index.md <<'EOF'
---
title: 블로그
summary: 포스트 모음
---
EOF

# tutorial 섹션
mkdir -p content/tutorial
cat > content/tutorial/_index.md <<'EOF'
---
title: 튜토리얼
summary: 실습 자료 정리
---
EOF
