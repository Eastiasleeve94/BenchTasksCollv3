# Final Pool

This folder contains the final pool of tasks that have been checked and
confirmed **implemented** as of the latest review. Each subfolder is one
implemented task, copied from its developer branch.

Included tasks (28):

analytics-dashboard, cache-optimizer, certificate-manager, client-portal,
customer-feedback-processor, discount-calculator, error-tracker,
expense-tracker, health-monitor, help-desk, inventory-management,
log-analyzer, loyalty-program, media-organizer, price-tracker,
robots-handler, scheduler, shipment-tracker, social-connector,
status-checker, storage-manager, streaming-service, survey-builder,
sync-service, tag-manager, task-scheduler, territory-manager, web-crawler

Implementation criteria (per `tasks/examples`):
- `docs/task.md` exists, is non-empty and written in English (no Chinese).
- `docs/agent_system_prompt.md` exists, is non-empty and in English.
- `docs/user_system_prompt.md`, if present and non-empty, is in English.
- `evaluation/main.py` exists.
- Other files (`preprocess/main.py`, `initial_workspace/`,
  `groundtruth_workspace/`) are present; only existence is checked.
