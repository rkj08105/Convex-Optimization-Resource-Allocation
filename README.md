# **Transfer Learning Based Resource Allocation**
This work demonstrates how the traditional optimization solution is not computationally demanding for generating training dataset for the scenario with perfect channel state information (CSI) as compared to the scenario with imperfect CSI. Therefore, in this work, we investigate the application of transfer learning to train a Deep Neural Network (DNN) model for joint channel and power allocation in underlay device-to-device (D2D) communication. Our transfer learning-based approach transfers the
DNN model trained for the perfect CSI scenario to the imperfect CSI scenario. Moreover, we also consider the issue of defining the similarity between two types of resource allocation tasks. For this, we first determine the value of outage probability for which two resource allocation tasks are same, that is, for which our numerical results illustrate the minimal need of relearning from the transferred DNN model. For other values of outage probability, there is a mismatch between the two tasks and our results illustrate a more efficient relearning of the transferred DNN model. Results demonstrate that the learning dataset required for relearning of the
transferred DNN model is significantly smaller than the required training dataset for a DNN model without transfer learning.

# **Required Knowledge:**
* Convex-Optimization
* Transfer Learning
* Deep Neural Network
* TensorFlow
* Python
* CVX Matlab

## **License**
* The project is licensed under the GNU General Public License v3.0.
* You may obtain a copy of the License at https://www.gnu.org/licenses/gpl-3.0.en.html

# **Citing Work**
* Rahul Jaiswal, Siddharth Deshmukh, Mohamed Elnourani, Baltasar Beferull-Lozano, Transfer learning Based Joint Resource Allocation for Underlay D2D Communications,
20th IEEE Wireless Communications and Networking Conference (WCNC) (2022), pp. 1479-1484. https://ieeexplore.ieee.org/document/9771636
