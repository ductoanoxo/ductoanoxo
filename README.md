# 📌 Portfolio & GitHub Profile — Trà Đức Toàn (ductoanoxo)

<p align="center">
   <img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&height=140&section=header&text=Tr%C3%A0%20%C4%90%E1%BB%A9c%20To%C3%A0n&fontSize=40&animation=twinkling&fontColor=ffffff" width="100%" alt="Header"/>
</p>

<p align="center">
  <a href="https://github.com/ductoanoxo">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=3B82F6&center=true&vCenter=true&width=750&lines=🚀+DevOps+Engineer+%7C+Infrastructure+Automation;🐳+Docker+Swarm+%7C+CI%2FCD+with+Jenkins;📈+Smart+Auto-Scaling+%26+Full-Stack+Observability;🤖+AI+System+Integrations+%7C+Agent+SQL+%26+RAG" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/ductoanoxo"><img src="https://img.shields.io/badge/GitHub-ductoanoxo-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="mailto:toantra349@gmail.com"><img src="https://img.shields.io/badge/Email-toantra349-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="tel:0965158329"><img src="https://img.shields.io/badge/Phone-0965158329-0088CC?style=for-the-badge&logo=telegram&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/School-Saigon%20University%20(SGU)-0056D2?style=for-the-badge&logo=education&logoColor=white"/>
  <img src="https://img.shields.io/badge/Location-Ho_Chi_Minh,_Vietnam-FF4B4B?style=for-the-badge&logo=googlemaps&logoColor=white"/>
</p>

---

## 🙋‍♂️ Giới Thiệu Bản Thân

Tôi là một kỹ sư **DevOps & Fullstack Developer** đam mê tự động hóa hạ tầng, tối ưu hóa quy trình triển khai và tích hợp các công nghệ AI tiên tiến vào ứng dụng thực tế. Với tư duy định hướng hệ thống vững chắc, tôi luôn cố gắng xây dựng các giải pháp phần mềm và hạ tầng chuẩn **production-ready**, có khả năng mở rộng tốt (scalability), độ tin cậy cao (reliability) và giám sát toàn diện (observability).

> **Phương châm làm việc:** *"If it's not automated, it's broken. If it's not observed, it's invisible."*

---

## 📌 Các Dự Án Tiêu Biểu (Featured Pinned Projects)

<div align="center">
  <a href="https://github.com/ductoanoxo/auto-deploy_stack">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ductoanoxo&repo=auto-deploy_stack&theme=tokyonight&show_owner=true" alt="Auto-Deploy Stack" />
  </a>
  <a href="https://github.com/ductoanoxo/Agent_SQL">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ductoanoxo&repo=Agent_SQL&theme=tokyonight&show_owner=true" alt="Agent SQL" />
  </a>
  <a href="https://github.com/ductoanoxo/AI-FOR-EDUCATION">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ductoanoxo&repo=AI-FOR-EDUCATION&theme=tokyonight&show_owner=true" alt="AI-FOR-EDUCATION" />
  </a>
</div>

---

## 🏆 Dự Án Trọng Tâm (Core Star Project)

### 🚀 [Auto-Deploy Stack — Full-Stack DevOps on Docker Swarm](https://github.com/ductoanoxo/auto-deploy_stack)

**Auto-Deploy Stack** là hệ thống DevOps end-to-end hoàn chỉnh mà tôi thiết kế và triển khai trên hạ tầng **AWS EC2 (Docker Swarm Cluster)** để tự động hóa hoàn toàn luồng phát triển và vận hành của một ứng dụng Fullstack (React + FastAPI).

<p align="center">
  <img src="160d9e2d-4fe0-4e1b-b608-94da3aac0ce5.png" alt="System Architecture Overview" width="100%" style="border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.15);"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Docker%20Swarm-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana%20Cloud-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/>
</p>

#### 🌟 Điểm Nhấn Kiến Trúc & Công Nghệ Cốt Lõi:

1. **🔄 Pipeline CI/CD Tự Động Hóa Hoàn Toàn (Jenkinsfile)**
   - Triển khai mô hình điều phối GitOps: `git push` → GitHub Webhook → Jenkins Trigger.
   - Build multi-stage Docker tối ưu dung lượng, tích hợp bộ kiểm thử tự động **Pytest**.
   - Rolling update **zero-downtime** và tự động rollback khi kiểm tra health check thất bại.

2. **📈 Hệ Thống Smart Auto-Scaling Tự Động Tải**
   - Cơ chế scale tự động dựa trên tải thực tế: **k6 Load Test (300 VU)** → **CPU Node > 80%** → **Grafana High CPU Alert (Firing)** → **Jenkins Webhook Trigger** → **Auto-Scale script** (`docker service scale frontend=3 backend=3`).
   - Tự động scale-down an toàn khi tải giảm liên tục dưới 30% để tối ưu tài nguyên AWS.

3. **🔭 Observability Stack Toàn Diện (LGTM)**
   - **Metrics & Logs**: Thu thập metrics hệ thống qua **cAdvisor**, **Swarm Exporter** và logs container qua **Grafana Alloy** đẩy trực tiếp về Grafana Cloud.
   - **Distributed Tracing**: Tích hợp **OpenTelemetry** trong FastAPI backend, chuyển traces về **Tempo** để debug hiệu năng từng API request một cách trực quan.

4. **💬 ChatOps Thông Minh Qua Telegram**
   - Tích hợp Telegram Bot thông báo kết quả build, trạng thái scale-up/down.
   - Hỗ trợ câu lệnh tương tác `/status` để quản trị viên truy vấn nhanh CPU%, RAM%, Disk% và danh sách container đang active ngay trên điện thoại.

---

## 💡 Các Dự Án AI & Công Nghệ Khác (Featured Ventures)

Bên cạnh mảng DevOps hạ tầng, tôi có kinh nghiệm chuyên sâu trong việc nghiên cứu và xây dựng các hệ thống AI ứng dụng (AI Agent & RAG) với kiến trúc Microservices hiện đại:

### 🎓 1. [AI Learning Studio — Nền Tảng AI Tạo Học Liệu Số](https://github.com/ductoanoxo/AI-FOR-EDUCATION)
*Nền tảng MVP hỗ trợ giáo dục thông minh giúp giáo viên và học sinh tạo nội dung học tập đa phương thức từ tài liệu số.*

*   **Tính năng chính:**
    *   **Advanced RAG Pipeline**: Sử dụng **Semantic Chunking** chia tài liệu theo ngữ nghĩa, kết hợp **Hybrid Search** (Chroma Vector Database + BM25 Keyword Search) và bộ tái xếp hạng **FlashRank Re-ranking** nâng độ chính xác câu trả lời lên tối đa.
    *   **AI Generator Worker**: Điều phối các tiến trình chạy nền phức tạp qua **Celery + Redis** để sinh tự động Slides thuyết trình (`.pptx`), Podcasts kịch bản đối thoại, Minigames (quizzes, flashcard), và chuyển đổi giọng nói (STT/TTS).
    *   **Interactive System**: Tích hợp **3D Mascot Assistant** tương tác qua Three.js, hỗ trợ truy cập web real-time (Tavily/SerpAPI) để tổng hợp kiến thức từ YouTube & Google.
*   **Tech Stack:** Next.js 14, FastAPI, MongoDB, ChromaDB, Redis, Celery, MinIO / Cloudflare R2, Docker.

---

### 🤖 2. [Agent SQL — Hệ Thống Đa Tác Vụ Multi-Agent NL2SQL](https://github.com/ductoanoxo/Agent_SQL)
*Hệ thống chuyển đổi ngôn ngữ tự nhiên thành truy vấn cơ sở dữ liệu và thực thi an toàn.*

*   **Tính năng chính:**
    *   **Multi-Agent Workflow**: Chia nhỏ tác vụ phân tích schema, tạo SQL tối ưu qua LLM (Gemini/GPT-4o Mini) và thực thi kiểm duyệt riêng biệt để đảm bảo an toàn dữ liệu.
    *   **Hỗ trợ đa nguồn dữ liệu**: Kết nối thông suốt 6 loại cơ sở dữ liệu: PostgreSQL (Supabase Connection Pooling), MySQL, MongoDB, Redis, SQLite và DuckDB (phục vụ OLAP phân tích tốc độ cao).
    *   **UI/UX Cao Cấp**: Dashboard trực quan hiển thị kết quả dạng bảng dữ liệu thô và biểu đồ phân tích tự động.
*   **Tech Stack:** FastAPI, Next.js, OpenRouter, Supabase, Docker Compose (Hot Reload).

---

## 🛠️ Hộp Công Cụ Công Nghệ (Tech Stack Matrix)

<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,jenkins,aws,prometheus,grafana,linux,nginx,python,fastapi,react,nextjs,typescript,postgres,supabase,mongodb,redis,git" alt="Tech Stack" />
</p>

| Lĩnh vực | Các công nghệ & Công cụ làm chủ |
|---|---|
| **DevOps & Cloud** | Docker, Docker Swarm, Jenkins, AWS (EC2, VPC, S3), Nginx, Portainer, Git |
| **Observability & Testing** | Prometheus, Grafana Cloud, Loki, Tempo, Grafana Alloy, OpenTelemetry, k6, Pytest |
| **Backend & AI Engine** | Python, FastAPI, Celery, LangChain, RAG, OpenRouter, Google Gemini, OpenAI APIs |
| **Frontend Development** | Next.js, React, TailwindCSS, TypeScript, HTML5/CSS3, Three.js |
| **Databases & Cache** | Supabase, PostgreSQL, MongoDB, Redis, MySQL, SQLite, DuckDB, MinIO |

---

## 📈 Bảng Hoạt Động & Thống Kê (GitHub Activity & Stats)

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ductoanoxo&theme=tokyonight&bg_color=1a1b27&color=38bdf8&line=38bdf8&point=e0f2fe&area=true&hide_border=true" width="100%" alt="GitHub Activity Graph" />
</p>

<div align="center">
  <table style="margin: 0 auto; border: none;">
    <tr style="border: none;">
      <td style="padding: 10px; border: none;">
        <img src="https://github-readme-stats.vercel.app/api?username=ductoanoxo&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
      </td>
      <td style="padding: 10px; border: none;">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ductoanoxo&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
      </td>
    </tr>
  </table>
</div>

---

<p align="center">
  Cảm ơn bạn đã ghé thăm trang cá nhân của tôi! Nếu bạn quan tâm đến các dự án trên, hãy thả một ⭐️ Star cho repo nhé! 
</p>

<p align="center">
  <b>Trà Đức Toàn</b> — <i>DevOps & Software Architect</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=80&section=footer" width="100%"/>
</p>
