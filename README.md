# Franka_PPO
Learn Graping Latch using PPO and IK

Prerequisites

    Ubuntu 18.04 or 20.04.

    Python 3.6, 3.7 or 3.8.

    Minimum NVIDIA driver version:

        Linux: 470

1. conda activate rlgpu first
2. export LD_LIBRARY_PATH=/home/jimmy/anaconda3/envs/rlgpu/lib
3. python franka_latch_ik_lift_cpu_solve.py \
  --num_envs 16 \
  --eval \
  --headless \
  --debug_print \
  --checkpoint ppo_latch_free_v9.pt
