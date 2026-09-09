<img src="assets/profile-cover.png" alt="Александр Кондаков — портрет, спутниковый снимок льда и архитектурная модель" width="100%">

# Александр Кондаков

**ML-инженер** &nbsp; · &nbsp; ИТМО, КТ &nbsp; · &nbsp; Санкт-Петербург

[Написать в Telegram](https://t.me/kndch_22) &nbsp; · &nbsp; [Почта](mailto:sanchousick-work@outlook.com) &nbsp; · &nbsp; [OpenReview](https://openreview.net/profile?id=~Aleksandr_Kondakov1) &nbsp; · &nbsp; [Codeforces](https://codeforces.com/profile/Sanchousick)

Разрабатываю ML-системы — от моделей и валидации до сервисов и запуска. Работаю с табличными данными, последовательностями, рекомендациями и LLM. Основатель и CTO стартапа: формируем ведомости объёмов работ и сметы по 3D/BIM-моделям зданий.

<sub>Открыт к стажировкам в ML / LLM / Data Science · до 40 часов в неделю · офис, гибрид или удалённо</sub>

<br>

## Избранные работы

<sub>МАШИННОЕ ОБУЧЕНИЕ · OZON TECH E-CUP 2026</sub>

### Прогноз покупательского GMV

**9 место из 678 команд.** Разработал 12 из 14 моделей финального ансамбля и протокол валидации. Последовательностные модели, табличный ML и калибровка.

<sub>RMSLE 1.6624 · у победителя — 1.6602</sub>  
[Репозиторий →](https://github.com/Kondachello/ozon-ecup-2026-gmv-forecasting)

<br>

<sub>ИССЛЕДОВАНИЯ · SMILES 2026</sub>

### Проверка утверждений в RAG

**ROC-AUC 0.849.** Детекция галлюцинаций через графы знаний и верификацию атомарных утверждений. Прирост +0.095 к воспроизведённому бейзлайну; соавтор статьи.

[Репозиторий →](https://github.com/Kondachello/rag-hallucination-detection) &nbsp; · &nbsp; [Статья →](https://openreview.net/forum?id=5nEiOJwG17)

<br>

<sub>КОМПЬЮТЕРНОЕ ЗРЕНИЕ · AI BUSINESS SPB 2026</sub>

### Восстановление спутниковых карт

**1 место на хакатоне.** Восстановление пропусков на картах ледовой обстановки: ResNet34 U-Net, геопространственные признаки, обучение с DDP/AMP.

<sub>mIoU 0.72 · Accuracy 0.96</sub>  
[Репозиторий →](https://github.com/Bibas-Bobas/ai-business)

<br>

<details>
<summary><b>Ещё пять проектов</b> — агенты, рекомендации, антифрод и инфраструктура</summary>

**[LLM-агент для генерации признаков](https://github.com/Kondachello/llm-feature-engineering-agent)**  
LangGraph-агент: гипотезы, код, песочница и отбор признаков. ROC-AUC 0.65+ на незнакомых табличных задачах за 500 секунд

**[Рекомендательная система VK Music](https://github.com/Kondachello/vk-music-recsys)**  
Implicit ALS, разреженные матрицы и холодный старт. **1 место**, Recall@50 0.25, NDCG@50 0.15

**[Антифрод Data Fusion](https://github.com/Kondachello/datafusion-2026-antifraud)**  
Self-supervised предобучение GRU и CatBoost-бейзлайн. **+0.02 PR-AUC** от последовательностного подхода

**[MLSecOps-платформа](https://github.com/Kondachello/mlsecops-platform)**  
Безопасная доставка моделей поверх MLflow, CI-гейты и аудит. Сквозной MVP для программы Альфа-Банк × «Сириус»

**[AI-интервьюер](https://github.com/Kondachello/ai-interviewer)**  
Мультиагентный сценарий интервью и изолированный запуск кода. Проект VibeCode Jam 2025

</details>

<br>

## Опыт и инструменты

- **Университет ИТМО** — бакалавриат «Прикладная математика и информатика», кафедра КТ, 2024–2028; курсы ШАД по Python, Rust и программированию на CUDA/C++.
- **Альфа-Банк × Университет «Сириус»** — программа «Безопасность технологий ИИ: от разработки до эксплуатации», конкурсный отбор, 2026.
- **SMILES 2026** — летняя школа машинного обучения, Skoltech AI Center.

<details>
<summary>Соревнования и достижения</summary>

- **1 место** — хакатон AI Business SPb 2026: восстановление пропусков на спутниковых картах ледовой обстановки, ResNet34 U-Net, **mIoU 0.72**.
- **1 место** — хакатон VK Music × БДиМО 2024: рекомендательная система на ALS с обработкой холодного старта.
- **9 место из 678 команд** — Ozon Tech E-CUP 2026: прогноз GMV пользователей; разработал 12 из 14 моделей финального ансамбля и протокол валидации.
- **ROC-AUC 0.849** — верификация утверждений для детекции галлюцинаций в RAG; соавтор статьи на SMILES 2026.
- Победитель олимпиад РСОШ по математике · Codeforces Specialist, рейтинг 1438.

</details>

<details>
<summary>Технологии</summary>

- **ML / DL:** PyTorch, CatBoost, LightGBM, XGBoost, scikit-learn, implicit, трансформеры, GRU, self-supervised learning, калибровка и ансамблирование
- **LLM-системы:** LangGraph, LangChain, RAG, графы знаний, structured outputs, оценка пайплайнов, изолированное исполнение кода
- **Данные:** Pandas, Polars, PyArrow, NumPy, SciPy, PostgreSQL, rasterio, OpenCV
- **Разработка:** Python, C++, Rust, SQL, Bash, FastAPI, Docker, MLflow, GitHub Actions, Redis, MinIO, pytest, Linux

</details>

<details>
<summary>Публикация</summary>

A. Maslov, E. Rutkovskii, N. Gavrishok, **A. Kondakov**. *What Does the Graph Contribute? Evidence-Grounded Claim Verification for RAG Hallucination Detection.* SMILES 2026 Projects & Proceedings, Skoltech AI Center. [OpenReview](https://openreview.net/forum?id=5nEiOJwG17) · [Код](https://github.com/Kondachello/rag-hallucination-detection)

</details>
