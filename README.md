# Kenya Forest Sounds Dataset

**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

## Authors and Contributors

All authors and contributors are listed on Zenodo:

- https://zenodo.org/records/19644980

---

## About

The **Kenya Forest Sounds Dataset** contains **5,500 audio recordings** collected during excursions to three forests in the Kenyan South Rift region:

- **Oloolua Forest** (Kajiado County)
- **Ngong Hills Forest Reserve** (Kajiado County)
- **Nyangores Forest** (Bomet County)

The primary purpose of this dataset is to address the limited availability of natural sound recordings from tropical forest ecosystems. The dataset can be used for machine learning classification tasks that detect and classify natural sounds occurring in forest environments.

### Potential Use Cases

1. Detecting human conversation in forest ecosystems.
2. Identifying Swahili-English human conversations.
3. Acoustic biodiversity and environmental monitoring.
4. Training and evaluation of audio classification models.

---

## Dataset Structure

1. Audio files are provided in **WAV format** using the naming convention:
   ```text
   ZOOM0XXX_X_16k.wav
   ```
2. Clip durations range from **0.07 seconds to 5.02 seconds**.
3. The dataset README (Dataset_Description.xlsx) contains two annotation tabs:
   - **Human-Annotated**
   - **ML-Annotated-People-Talking**
4. The **Human-Annotated** subset contains **3,164** sounds labelled by human annotators.
5. The **ML-Annotated-People-Talking** subset contains **2,336** sounds of human conversation detected by a pre-trained model and subsequently validated by human annotators.
6. Details of the ML annotation workflow are available at:
   - https://github.com/SCES-Makerspace-Lab/Auto-Sound-Annotation-2026

---

## Sound Labels

The dataset contains the following labels (including original label naming conventions):

- Axe
- Bag
- Bag Zip
- Birds
- Car Passing
- Chainsaw
- Child
- Cow Mooing
- Creaking
- Crickets
- Cutting Wood
- Distant Talking
- Distrubance Noise
- Disturbance Noise
- Drone
- Engine
- Flowing Water
- Livestock
- Machine Beeping
- Machine Moving
- Motorcycle
- Moving Machine
- Moving Object
- Moving Objects
- Moving Vehicle
- Objects Moving in Water
- Objects Moving
- Passing Vehicle
- People Taling
- People Talking
- People Talking and Laughing
- Person Laughing
- Person Moving
- Person Singing
- Person Talking
- Person Talking Over Disturbance Noise
- Person Talking (Far)
- Person Walking
- Phone
- Plastic Wrapper
- Pouring Water
- Radio
- Shuffling
- Sloshing Water
- Sloshing Water and Talking
- Steel Banging
- Talking
- Vehicle
- Wind

---

## Citation and Attribution

When using this dataset, please cite the dataset record available on Zenodo:

https://zenodo.org/records/19644980
