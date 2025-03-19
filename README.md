# BIP-task3

# How to use the processed_data
Make sure you follow these code hint:
'''python
TRAIN_IMAGES = "train_60m_images.npy"
TRAIN_LABELS = "train_60m_labels.npy"

VAL_IMAGES   = "val_60m_images.npy"
VAL_LABELS   = "val_60m_labels.npy"

TEST_IMAGES  = "test_60m_images.npy"
TEST_LABELS  = "test_60m_labels.npy"

BATCH_SIZE = 64
LR         = 1e-3
NUM_EPOCHS = 10
DEVICE     = "cuda" if torch.cuda.is_available() else "cpu"
'''
You can modify it as you like!