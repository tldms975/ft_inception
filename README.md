## 🔧 환경 변수 설정 (.env)

본 프로젝트는 `.env` 파일이 없으면 실행되지 않습니다.  
아래 형식을 참고해 ./srcs 디렉토리에 `.env` 파일을 작성해 주세요:

```env
# certificates ----------
INTRA_ID=your_intra_id

# mysql ----------
MYSQL_DB=your_db_name
MYSQL_HOST=your_db_host
MYSQL_ROOT_PASSWORD=your_root_password
MYSQL_USER=your_db_user
MYSQL_PASSWORD=your_db_password

# wordpress ----------
DOMAIN_NAME=your.domain.com
WP_TITLE=your_site_title
WP_ADMIN_USER=your_admin_id
WP_ADMIN_EMAIL=your_admin_email
WP_ADMIN_PASSWORD=your_admin_password
WP_USER=your_user_id
WP_USER_EMAIL=your_user_email
WP_USER_PASSWORD=your_user_password
