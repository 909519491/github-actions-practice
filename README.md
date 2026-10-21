# github-actions-practice

我的第一个 GitHub Actions 实践：使用 GitHub Actions 对 Python 项目（计算器）实现自动化单元测试。

- `calculator.py`：被测试的代码（加法、乘法）
- `test_calculator.py`：pytest 测试代码
- `.github/workflows/ci.yml`：GitHub Actions 工作流配置（push / PR 时自动运行 pytest）
