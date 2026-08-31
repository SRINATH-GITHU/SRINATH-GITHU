- 👋 Hi, I’m @SRINATH
- 👀 I’m interested in Software Development
- 🌱 I’m currently learning Full Stack Development
- 💞️ I’m looking to collaborate on Project
- 😄 Pronouns: He

Subject: Proposal: Replay Training for Multi-Class Detection

Hi [Manager's Name],

I wanted to update you on our object detection model optimization.

When adding new custom classes (like pen or knife) alongside base classes (like laptop or phone), standard fine-tuning leads to catastrophic forgetting, where the model loses baseline class accuracy. Conversely, running an ensemble/multi-model setup avoids forgetting but drastically increases GPU computation and latency.

Proposed Solution: Replay (Rehearsal) Joint Training
To solve both issues, we plan to train a single combined multi-class model using a balanced dataset of new custom images and a representative subset of original base class data.

This approach prevents catastrophic forgetting while keeping inference fast and resource-efficient on a single GPU.

Let me know if you would like to discuss this further before we begin training.

Best regards,

[Your Name]

