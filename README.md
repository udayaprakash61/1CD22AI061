# 1️⃣ AlexNet.py – Code Changes

# Original Issues
- Outdated Keras syntax
- Missing explicit input definition
- TensorFlow 2.x incompatibility

# Modifications Made
- Added `Input()` layer
- Updated convolution and pooling syntax
- Removed deprecated parameters
- Improved code readability

# Result
- Fully compatible with TensorFlow 2.x
- Correct model construction and summary
- Architecture aligns with standard AlexNet

# 2️⃣ Image-Classification CNN – Code Changes

# Original Issues
- Hard-coded dataset paths
- Manual dataset management
- Deprecated optimizer arguments
- Unsafe system calls

# Modifications Made
- Switched to built-in `cats_vs_dogs` dataset
- Used `tf.data` pipeline instead of directory loaders
- Updated optimizer parameters
- Added early stopping for stable training

# Result
- No manual downloads required
- Faster and cleaner training
- Portable and exam-friendly code

# 3️⃣ Deep Reinforcement Learning – Code Changes

# Original Issues
- Incorrect random action selection
- Use of deprecated NumPy matrix types
- Redundant and unclear logic

# Modifications Made
- Replaced `np.matrix` with `np.array`
- Simplified Q-learning update rule
- Fixed action selection mechanism
- Cleaned reward matrix initialization

# Result
- Stable Q-learning convergence
- Correct optimal path discovery
- Improved code clarity

# 4️⃣ LSTM Time Series Forecasting – Code Changes

# Original Issues
- CSV loading errors
- Incorrect input shape for LSTM
- Deprecated imports

# Modifications Made
- Fixed CSV reading logic
- Normalized data correctly
- Ensured proper LSTM input dimensions
- Updated Keras imports

# Result
- Smooth training without runtime errors
- Accurate sequence prediction
- Clean preprocessing pipeline

# 5️⃣ RNN Text Generation – Code Changes

# Original Issues
- Limited learning with SimpleRNN
- Inefficient one-hot encoding
- Repetitive text generation

# Modifications Made
- Replaced `SimpleRNN` with `LSTM`
- Used `Embedding` layer instead of one-hot encoding
- Improved text generation logic
- Cleaned dataset preparation

# Result
- Better memory handling
- More natural text generation
- Industry-standard implementation

# 6️⃣ Tic Tac Toe Reinforcement Learning – Code Changes

# Original Issues
- Incorrect player initialization
- Reward propagation bugs
- State storage inconsistencies
- Player turn switching errors

# Modifications Made
- Fixed player symbol initialization
- Corrected reward assignment
- Cleaned win/draw detection
- Added policy save/load support
- Separated training and gameplay logic
# Result
- Stable reinforcement learning
- AI learns optimal strategies
- Human vs AI gameplay works corrected
Install dependencies:
```bash
pip install tensorflow tensorflow-datasets numpy matplotlib
