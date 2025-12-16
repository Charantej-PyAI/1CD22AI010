RNN 

Previous Issues

Hard-coded inputs, 
No batching, 
No sequence padding, 
No loss curve logging

Improvements

Implemented PyTorch nn.LSTM and nn.RNN properly, 
Added batching with DataLoader, 
Added sequence padding nn.utils.rnn.pad_sequence, 
Added teacher forcing for training stability, 
Training loop improved with:
Gradient clipping
Scheduler
Validation step

