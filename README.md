# Abstract
Atrial fibrillation (AF) is a prevalent arrhythmia that significantly increases the risk of stroke, heart failure, and other complications. Traditional detection methods, such as Holter monitors, are effective but often cumbersome for long-term monitoring. Recent advances in wearable technology, including patch and wrist-type ECG devices, offer promising alternatives but face limitations in user comfort and continuous monitoring feasibility. This study introduces a novel PPG/ECG cooperative wearable device that leverages photoplethysmography (PPG) for continuous heart rate (HR) monitoring and electrocardiography (ECG) for precise AF detection. The system uses PPG for preliminary AF screening and prompts ECG measurements upon detecting irregularities, with data transmitted to medical professionals for confirmation. We propose a robust motion artifact (MA) cancellation algorithm and an AF-finite state machine (AF-FSM) framework to enhance detection accuracy. 

# Reference AF and NSR dataset
BAMI-I : https://github.com/hooseok/BAMI1 \
BAMI-II : https://github.com/hooseok/BAMI2 \
MIMIC PERform Datasets : https://zenodo.org/records/6973963


# Results for plot
refBPM : ECG Heart Rates \
estBPM : Estimated Heart Rates \
State : Estimated Finite State Machine States \
CF : Crest Factor in PPG signals \
HRchange : Heart Rate changes from estBPM

# AF Results
refineBPM : Estimated Heart Rates \
bpmState : Estimated Finite State Machine States \
RMSSDnor : Root mean square of successive RR differences \
SampleEN : Sample Entropy values \
shannonEntropy : Shannon Entropy values
