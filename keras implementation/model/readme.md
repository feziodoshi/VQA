Contains the different models json files

- **normal_2_gru_nodistributed_2hidden.json**:  2 stacked GRU + CNN(4096 features) + Feed Forward(2 hidden layers)
- **normal_2_lstm_nodistributed_2hidden.json**: 2 stacked LSTM + CNN(4096 features) + Feed Forward(2 hidden layers)
- **1_lstm_timedistributed_2hidden.json**: 1 LSTM + Time Distributed Dense + CNN(4096 features) + Feed Forward(2 hidden layers)
- **1_gru_timedistributed_2hidden.json**: 1 GRU + Time Distributed Dense + CNN(4096 features) + Feed Forward(2 hidden layers)

the label encoder simply encodes and decodes answers from text to a vector and vice-versa. 

