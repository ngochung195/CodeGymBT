Prompt 1: Đã hoàn thành việc đẩy lên Github chưa và có lỗi nào không?
D:\CodeGym\ThucHanhGit\CodeGymBT>git add .
D:\CodeGym\ThucHanhGit\CodeGymBT>git commit -m "first commit"
[main (root-commit) b443ab2] first commit
 2 files changed, 34 insertions(+)
 create mode 100644 TechBugs/ai_prompt_log.md
 create mode 100644 TechBugs/index.html
D:\CodeGym\ThucHanhGit\CodeGymBT>git branch -M main
D:\CodeGym\ThucHanhGit\CodeGymBT>git remote add origin https://github.com/ngochung195/CodeGymBT.git
error: remote origin already exists.
D:\CodeGym\ThucHanhGit\CodeGymBT>git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 777 bytes | 777.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ngochung195/CodeGymBT.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.


Prompt 2:Làm thế này đã đúng chuẩn Semantic chưa?
    <main>
        <section>
            <h2>Bài viết mới nhất</h2>

            <article>
                <h3>Hiểu về Git cơ bản</h3>
                <p>Git là hệ thống quản lý phiên bản phân tán...</p>
            </article>

            <article>
                <h3>Tại sao cần Semantic HTML?</h3>
                <p>Thẻ ngữ nghĩa giúp các công cụ tìm kiếm đọc hiểu trang web tốt hơn...</p>
            </article>
        </section>
    </main>
