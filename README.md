# 商品管理数据库

一个简单的商品管理数据库网页，数据实时读取自 [Supabase](https://supabase.com)（PostgreSQL）。

- 网页：`index.html`（纯静态，通过浏览器直接调用 Supabase REST API 读取数据）
- 数据源：`https://qecxgzyknjqjplrdcgzr.supabase.co`

## 本地数据操作

同目录下的 `main.py`（Python）用 `supabase` 库对数据进行增删改查：

```bash
pip install -r requirements.txt
python main.py
```
