- Merge commit:
  + Trong chế độ này bạn merge 1 pull request ,GitHub sẽ tạo 1 commit mới trên nhánh chính .Commit chứa tất cả các thay đổi từ Pull Request
  .Điều này làm cho lịch sử commit dễ hiểu hơn ,vì mỗi lền PR được Merge sẽ tạo 1 commit riêng.
- Squash and Merge:
  + Trong chế độ này tất cả các commit từ PR khi được Merge sẽ gộp thành 1 conmmit duy nhất .Nên chỉ có 1 commit đại diện cho tất cả các thay đổi
    của PR đó .Thường được dùng để làm gọn hơn và không cần sử dụng comment đó.
- Rebase and Merge:
  + Tại đây, thay vì tạo 1 commit mới hoặc gộp commit lại, Github sẽ chạy 1 rebase cho tất cả comment từ PR lên đầu của nhánh chính. Sau đó, những
   thay đổi sẽ được merge vào nhánh chính với lịch sử commit liền mạch hơn. Rebase có thể giữ cho lịch sử commit trông sạch sẽ hơn và ít phức tạp hơn so với merge commit,
   nhưng cũng có thể tạo ra những vấn đề nếu không được sử dụng đúng cách, đặc biệt là khi làm việc với nhiều người cùng lúc trên cùng một nhánh.
