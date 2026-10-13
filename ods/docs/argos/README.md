# Argos downstream preparation

This local downstream branch is based on Osmantic/ODS6ce91bcb090bf879f39723a926a2fed1e8c480b3 and retains the upstream remote. It is not yet a GitHub fork or an installed stack. No runtime credentials or personal records belong in this tree. Preserve upstream and third-party notices, including Pixel's ODS-only license.

Initial scope is native external llama.cpp inference, dashboard/chat, and a separate Argos bridge. Optional n8n, image generation, RAG, voice and other agent runtimes stay off. The OptiPlex owns task/history/checkpoint authority; the workstation owns replaceable compute. Browser prompts never approve admin access, OS switching or releases. Keep Argos extensions isolated from upstream core and generated runtime data.

The authoritative accepted integration plan and qualification evidence are maintained in the Argos repository's docs/ODS-INTEGRATION.md, docs/LOCAL-BUILDER-PLAN.md and docs/WORKSTATION-QWEN9-RESULTS.json. The selection file here is preparation metadata only. A reviewed resolved stack, pinned images, authenticated model route, independent checkpoint/recovery and phone/shared-task checks precede activation. Strict Local Only cannot silently fall back to a cloud route.

For upstream updates: fetch upstream, compare from the recorded full commit, review changed installer/runtime/extension contracts and licenses, then test in an isolated candidate. Retain this branch and source pin before accepting updates; do not overwrite a running installation from mutable main.
