# Final Pool

This folder collects every task that is marked **`implemented`** in the Notion
`Task Tracker` (Task Status Table) after the branch-by-branch review of the most
recent "Work on N tasks" commits of all developer branches of BenchTasksCollv3.

## Selection criteria (from `tasks/examples/example-task`)

A task is counted as **implemented** only when it satisfies the requirements stated in the example task:

* `docs/task.md` exists, is non-empty and written fully in English (no Chinese)
* `docs/agent_system_prompt.md` exists, is non-empty and written fully in English (no Chinese)
* `docs/user_system_prompt.md` is optional, but when present and non-empty it must be fully in English
* `evaluation/main.py` exists so the task can be evaluated (mandatory in practice)
* `preprocess/main.py`, `initial_workspace/` and `groundtruth_workspace/` are optional

Any task that fails one of the checks above is still **`implementing`** and is therefore not included here.

## Included tasks (77)

| developer branch | implemented tasks |
| --- | --- |
| fan-dev | coupon-manager, price-tracker, loyalty-program, discount-calculator |
| gyy | blog-engine, cms-builder, content-scheduler, social-publisher, tag-manager, robots-handler |
| haoze | subtitle-generator, video-trimmer, media-organizer, streaming-service |
| jl_dev | canvas-grade-automation, email-classification-system, pdf-report-generator, customer-feedback-processor, inventory-management |
| junteng_dev | booking-system, calendar-sync, contact-manager, order-processor, product-catalog, reminder-service, shipment-tracker, help-desk |
| junxian_dev | qr-generator, translation-api, social-connector |
| lueyang-dev | activity-logger, crm-system, deal-manager, email-campaign, follow-up-reminder, sales-pipeline, territory-manager, client-portal |
| lv | chat-bot, feedback-collector, personalization-service, sentiment-analyzer, voice-processor, survey-builder, analytics-dashboard |
| ruige | canvas-automation, data-analytics, expense-tracker, file-manager, web-crawler, log-analyzer |
| wenshuo-dev | image-processor, search-engine, cache-optimizer, scheduler |
| xiaochen_dev | backup-utility, deployment-tool, error-tracker, monitoring-agent, security-scanner, health-monitor, status-checker |
| yuxuan-dev | asset-optimizer, content-manager, network-analyzer, task-scheduler, sync-service |
| yuzhen-dev | alert-system, data-validator, form-builder, invoice-generator, payment-processor, permission-manager |
| zhaochen | load-balancer, template-engine, certificate-manager, storage-manager |

Each task keeps its original layout, e.g. `tasks/finalpool/<task>/docs/task.md`.

## Still implementing (excluded)

currency-converter, insights-engine, audit-logger and resource-monitor contain Chinese text in their docs (violates the English-only requirement of `tasks/examples`); sitemap-generator and customer-portal are still missing `evaluation/main.py`.
