# Plant-Species-Images-Classification Laboratory Work 2-A Activity 
Plant Species Image Classification Using Teachable Machine

A. Project Overview This project presents an image classification model developed to recognize 20 distinct plant species. Utilizing a dataset of 5000 images, the model was trained to differentiate among various plant morphological features, including structural characteristics, leaf patterns, and color variations. The system is intended to support gardeners and botany students in the efficient identification of common ornamental and wild plant species. 

## B.🌿 Plant Species Gallery

| Common Name | Scientific Name | Description | Image |
|-------------|-----------------|-------------|-------|
| Silver Inch Plant | Tradescantia zebrina | Known for its purple-and-green striped leaves with silvery, iridescent bands. | <img src="https://github.com/user-attachments/assets/f4b215e4-c48d-46f0-8f2a-f0b3407db168" width="120"/> |
| Makahiya | Mimosa pudica | Famous for its leaves folding inward when touched. | <img src="https://github.com/user-attachments/assets/4726b0e2-fe5e-4c7f-a1f2-0fb02bb3aa02" width="120"/> |
| Sikwati | Luffa aegyptiaca | A fast-growing tropical vine producing smooth, cylindrical fruits. | <img src="https://github.com/user-attachments/assets/c9df23dc-7815-48f7-85a5-5d3566b92134" width="120"/> |
| Cassava | Manihot esculenta | Palm-like leaves splayed from a central point, variable in size and shape. | <img src="https://github.com/user-attachments/assets/7f84763d-e911-462d-8366-9b2aa8b92db8" width="120"/> |
| Lady Palm | Rhapis | Slender bamboo-like trunks with glossy, dark green fan-shaped leaves. | <img src="https://github.com/user-attachments/assets/a198056a-2de1-46d9-b775-eb1f63db3609" width="120"/> |
| Alugbati | Basella alba | Tropical leafy green with succulent leaves and mild pepper-lemon flavor. | <img src="https://github.com/user-attachments/assets/02762538-928b-4d08-a8db-92c4698f2a43" width="120"/> |
| Pinya | Ananas comosus | Tropical perennial known for its sweet, juicy yellow fruit. | <img src="https://github.com/user-attachments/assets/d14a409b-2f82-4118-a278-61909457c9eb" width="120"/> |
| Plumed Cockscomb | Celosia argentea | Features feathery, flame-like, brightly colored spikes. | <img src="https://github.com/user-attachments/assets/62d41c73-d34a-4a7d-b35c-2d0750b086e3" width="120"/> |
| Peanut Plant | Arachis hypogaea | Has pinnate leaves with four leaflets and small yellow flowers. | <img src="https://github.com/user-attachments/assets/dce1a298-4634-499d-9293-741d5263dab9" width="120"/> |
| Kalabo | Plectranthus amboinicus | Recognized for thick, fuzzy, aromatic leaves. | <img src="https://github.com/user-attachments/assets/341527cd-ee94-4539-926c-250533ef3da4" width="120"/> |
| peacock flower plant | Caesalpinia pulcherrima | Produces year-round red, orange, and yellow flowers. | <img src="https://github.com/user-attachments/assets/e14ccdc6-96bd-416d-ab41-6955c9938166" width="120"/> |
| Giant Squill  | Drimiopsis maculata | Heart-shaped glossy leaves heavily covered in dark spots. | <img src="https://github.com/user-attachments/assets/35e1a399-2c58-4866-9ed1-05b71626ce95" width="120"/> |
| False Shamrock | Oxalis triangularis | Known for its distinctive triangular leaves. | <img src="https://github.com/user-attachments/assets/23b22eb6-b4fb-4bc1-83e9-b09275f487c3" width="120"/> |
| Zig-zag Plant | Euphorbia tithymaloides | Hardy shrub with distinctive zig-zagging stems and variegated leaves. | <img src="https://github.com/user-attachments/assets/91de3e80-8a69-4c7c-bc72-49435d62b1c5" width="120"/> |
| Gabi | Colocasia esculenta | Large heart-shaped leaves and edible underground corm. | <img src="https://github.com/user-attachments/assets/d234c974-b9f3-4aff-ab6e-4dee23ae6e87" width="120"/> |
| Heart of Jesus | Caladium bicolor | Features large variegated heart-shaped leaves in vivid colors. | <img src="https://github.com/user-attachments/assets/6ae593dc-1935-49d3-8bfb-0f3163138c2e" width="120"/> |
| Summer Torch | Bromeliaceae | Rosette-shaped foliage with vibrant long-lasting bracts. | <img src="https://github.com/user-attachments/assets/ba7b62e5-9ede-4766-8b33-655f8e4fba3d" width="120"/> |
| Boat Lily | Tradescantia spathacea | Waxy sword-shaped leaves, green on top and purple underneath. | <img src="https://github.com/user-attachments/assets/7263c345-c5e1-4a8c-ba61-53c7633b0568" width="120"/> |
| Begonia sericoneura | Begonia sericoneura Liebmann | Noted for its soft, hairy foliage. | <img src="https://github.com/user-attachments/assets/6fb87a00-e66c-498b-817a-c75c1b6d3f7f" width="120"/> |
| Balanoy | Ocimum basilicum | Aromatic herb with glossy green leaves and sweet flavor. | <img src="https://github.com/user-attachments/assets/d57f7c70-0494-4d7e-9caa-517c85262ffc" width="120"/> |



## 🧪 C. Model Testing

Below are 10 tests performed using images the model had not seen during training. These results demonstrate the model's ability to generalize and accurately identify plant species under various conditions.

| Test | Plant | Result | Confidence | Image(s) |
|------|-------|--------|------------|----------|
| Test 1 | Malabar Spinach / Alugbati | ✅ Correct | 100% | <img src="https://github.com/user-attachments/assets/45f41458-e41b-4975-b270-d5347771981b" width="120"/> |
| Test 2 | Sweet Basil / Balanoy | ✅ Correct | 100% | <img src="https://github.com/user-attachments/assets/e30884e6-40ed-44df-94f5-7502ec194978" width="120"/> <img src="https://github.com/user-attachments/assets/8ea9548e-724a-47dd-a594-8d14505250ee" width="120"/> |
| Test 3 | Silver Inch Plant | ✅ Correct | 100% | <img src="https://github.com/user-attachments/assets/b89e4900-dfe0-49f8-8745-ebb51618f7b1" width="120"/> |
| Test 4 | Makahiya / Shameplant | ✅ Correct | 100% | <img src="https://github.com/user-attachments/assets/a1db445f-ecaf-4734-8ae0-de855e7dffe1" width="120"/> |
| Test 5 | Cassava | ✅ Correct | 100% | <img src="https://github.com/user-attachments/assets/30115f00-2d7e-4094-9d4a-63990464c914" width="120"/> |
| Test 6 | Rhapis (Lady Palm) | ✅ Correct | 100% | <img src="https://github.com/user-attachments/assets/53c6ed0c-e5c9-450a-a710-6c2678a2f798" width="120"/> |
| Test 7 | Asunting / Peacock Flower | ✅ Correct | 100% | <img src="https://github.com/user-attachments/assets/3ce07c8c-2365-4df1-a6fc-4e5b3bf7385c" width="120"/> |
| Test 8 | False Shamrock | ✅ Correct | 100% | <img src="https://github.com/user-attachments/assets/05ecc856-c8a1-414d-8b4c-83e3a9cedc3b" width="120"/> <img src="https://github.com/user-attachments/assets/735884b8-e1c2-4bdb-a133-60e4dadfa23f" width="120"/> |
| Test 9 | Zig-zag Plant / Devil’s Backbone | ✅ Correct | 100% | <img src="https://github.com/user-attachments/assets/98f27c79-14fb-4b8a-ab24-0087e772bc48" width="120"/> <img src="https://github.com/user-attachments/assets/c6f47951-e718-4135-9eab-6629e30c3d06" width="120"/> |
| Test 10 | Gabi / Taro | ✅ Correct | 100% | <img src="https://github.com/user-attachments/assets/77efb0b6-35d6-4458-8e8c-e5dd8d956e84" width="120"/> <img src="https://github.com/user-attachments/assets/0620f278-a9a4-42e8-b49a-7741fcb4b9b9" width="120"/> |




---

## 📊 D. Dataset and Training Configuration

### Dataset Distribution
- **Total Images:**  5,000
- **Number of Classes:** 20 plant species
- **Images per Class:** ~250 images per class (distribution varies by species)


### Class Distribution
The dataset encompasses 20 distinct plant species with approximately 250images per class, though some species have slightly more or fewer samples based on availability and morphological diversity requirements.

---

## 📈 E. Model Performance Evaluation


### Confusion Matrix Analysis
The confusion matrix below illustrates the model's classification performance across all 20 plant species, with strong diagonal dominance indicating accurate predictions.

<img width="378" height="296" alt="image" src="https://github.com/user-attachments/assets/5e5ae9dd-76a3-42d1-bf7d-bc4ab7c8d5f6" />


*Figure 1: Confusion matrix showing classification results across all 20 plant species. Darker diagonal cells indicate higher prediction accuracy.*

### Accuracy & Loss Curves
The training and validation curves demonstrate consistent learning without significant overfitting, as both accuracy and loss metrics converge smoothly.

<img width="374" height="291" alt="image" src="https://github.com/user-attachments/assets/4ae69796-0c16-4bcc-9fd1-2293488a3432" />

*Figure 2: Training and validation accuracy (left) and loss (right) over 100 epochs. The close alignment between training and validation curves suggests good generalization.*


