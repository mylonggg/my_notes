1.创建Workers 和 Pages
2.创建D1 SQL数据库
3.代码
、、、bash
DROP TABLE IF EXISTS notes;
CREATE TABLE IF NOT EXISTS notes (
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  content TEXT NOT NULL,
  public_id TEXT,
  is_share_copy INTEGER DEFAULT 0,
  created_at DATETIME DEFAULT CURRENT_TIMESTAMP
);
、、、
