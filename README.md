# UBC Course Skippability Guide  
UBC选择性上课指南

A practical, crowdsourced guide to UBC courses — not just about what the course *teaches*, but about whether you *need to show up*. This project evaluates the skippability of lectures, labs, tutorials, and other components, with an emphasis on how each part affects grades, learning outcomes, and time efficiency.

一个由学生共同维护的UBC课程指南项目。不同于官方课程描述，本项目关注每门课程中哪些部分值得投入时间，哪些可以选择性出席，哪些完全可以放心翘课，哪些虽然可以翘课但强烈建议参与。目标是帮助学生优化出勤策略，提高时间使用效率。

---

## Project Goals / 项目目标

- Identify which parts of a course are mandatory, impactful, or dispensable  
  明确课程中的哪些环节是强制的、重要的，哪些影响较小或可以跳过
- Estimate effort vs. reward for each course component  
  提供每部分的“投入-产出”评估（对成绩、知识掌握的影响）
- Enable strategic attendance and time planning  
  帮助制定基于出勤性价比的排课与出勤策略

---

## Repository Structure / 仓库结构

- Each course has a Markdown file: `courses/<Department>/<CourseCode>/<CourseCode_instructor_term>.md`  
  每门课程以 Markdown 文件记录，放在 `courses/<院系>/<课程编号>/<课程编号__教师__学期>.md`
- Example: `courses/CPSC/CPSC110/CPSC110__GregorKiczales__2023W1.md`

每个文件应基于模板包含以下部分：
- Course overview (term, instructor) / 课程基本信息
- Skippability table / 各模块出勤评估表
- Workload estimates / 工作量估计
- Grading scheme / 评分构成
- Suggestions / 选课建议

---

## How to Contribute / 如何参与贡献

We welcome all contributions from students who have taken UBC courses. If you’ve taken a course recently, consider contributing your experience in the standard format.

我们欢迎所有曾经上过UBC课程的同学参与撰写。只要你记得每周都在干什么、作业有多难、出勤有没有用，就可以写。

### Steps / 投稿步骤

1. Fork this repository  
2. Add a new course file or edit an existing one under `courses/`
3. Follow the format in [`TEMPLATE.md`](TEMPLATE.md)
4. Submit a pull request with course name, term, and instructor in the title

---

## Content Policy / 内容规范

Please **do not** include:
- Assignment answers or exam questions  
- Any copyrighted material  
- Screenshots or internal links to course systems (Canvas, etc.)

请**不要**提交以下内容：
- 作业答案或考试题
- 教材内容或未授权的教学材料
- 内部系统截图（如Canvas）

---

## License / 开源协议

This project is licensed under the **MIT License**.  
You are free to use, copy, modify, and redistribute contributions under the terms of the license.  
By submitting content, you agree to license your contribution under MIT and affirm that your writing is original and compliant with academic integrity standards.

本项目遵循 **MIT 开源协议**，你可以自由使用、修改、转载本仓库的内容。提交内容即代表你同意按该协议开源，并确认你的内容原创且不违反UBC学术诚信政策。

---

## Contact

If you’d like to contribute in bulk, help moderate, or integrate the content into a web app, please reach out via Issues or Pull Requests.

如希望大规模投稿、协助管理、或制作网页版本，可通过 GitHub Issue 与我们联系。
