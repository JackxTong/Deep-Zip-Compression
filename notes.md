Running `bash compress.sh files_to_be_compressed/hmm10.txt hmm10.dzip com MODEL_PATH`

Output log:

```
Seq Length 10000000
Using cuda
Vocab Size 2
CudNN version 90100
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
0.999748706817627 secs
3.009756326675415 secs/4882 Average loss: 1.3487
2.8751566410064697 secs1/4882 Average loss: 0.8183
2.91487193107605 secs1001/4882 Average loss: 0.6480
2.8692355155944824 secs01/4882 Average loss: 0.5909
2.925393581390381 secs001/4882 Average loss: 0.5624
2.8688416481018066 secs01/4882 Average loss: 0.5448
2.854135513305664 secs001/4882 Average loss: 0.5329
2.8583834171295166 secs01/4882 Average loss: 0.5246
2.8637025356292725 secs01/4882 Average loss: 0.5180
====> Epoch: 1 Average loss: 0.5097038759ss: 0.5129
Loss went from 100000000.0000 to 0.5097
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
0.5534250736236572 secs
2.963128089904785 secs/4882 Average loss: 0.4404
2.860232353210449 secs01/4882 Average loss: 0.4724
2.8918464183807373 secs01/4882 Average loss: 0.4727
2.8481180667877197 secs01/4882 Average loss: 0.4716
2.8800384998321533 secs01/4882 Average loss: 0.4721
2.788412094116211 secs501/4882 Average loss: 0.4723
2.7890729904174805 secs01/4882 Average loss: 0.4723
2.8169660568237305 secs01/4882 Average loss: 0.4719
2.784167528152466 secs001/4882 Average loss: 0.4718
====> Epoch: 2 Average loss: 0.4712413291ss: 0.4714
Loss went from 0.5097 to 0.4712
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
0.5564084053039551 secs
2.8701329231262207 secs4882 Average loss: 0.4834
2.836047887802124 secs01/4882 Average loss: 0.4687
2.848097562789917 secs001/4882 Average loss: 0.4713
2.865919589996338 secs501/4882 Average loss: 0.4713
2.8615427017211914 secs01/4882 Average loss: 0.4705
2.9025115966796875 secs01/4882 Average loss: 0.4701
2.8219187259674072 secs01/4882 Average loss: 0.4700
2.8219125270843506 secs01/4882 Average loss: 0.4706
2.81469464302063 secs4001/4882 Average loss: 0.4706
====> Epoch: 3 Average loss: 0.4702934319ss: 0.4706
Loss went from 0.4712 to 0.4703
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
0.5419130325317383 secs
2.8659250736236572 secs4882 Average loss: 0.4906
2.7978508472442627 secs1/4882 Average loss: 0.4692
2.8253564834594727 secs01/4882 Average loss: 0.4691
2.804335832595825 secs501/4882 Average loss: 0.4703
2.7963595390319824 secs01/4882 Average loss: 0.4710
2.8321619033813477 secs01/4882 Average loss: 0.4704
2.79723858833313 secs3001/4882 Average loss: 0.4700
2.920790672302246 secs501/4882 Average loss: 0.4700
2.8848304748535156 secs01/4882 Average loss: 0.4698
====> Epoch: 4 Average loss: 0.4696960098ss: 0.4698
Loss went from 0.4703 to 0.4697
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
0.5420703887939453 secs
2.886096239089966 secs/4882 Average loss: 0.4724
2.833543539047241 secs01/4882 Average loss: 0.4700
2.8973920345306396 secs01/4882 Average loss: 0.4700
2.869391441345215 secs501/4882 Average loss: 0.4714
2.8670902252197266 secs01/4882 Average loss: 0.4707
2.897735357284546 secs501/4882 Average loss: 0.4701
2.8624520301818848 secs01/4882 Average loss: 0.4699
2.8851842880249023 secs01/4882 Average loss: 0.4698
2.8526389598846436 secs01/4882 Average loss: 0.4695
====> Epoch: 5 Average loss: 0.4697283552ss: 0.4697
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
0.5561342239379883 secs
2.9385154247283936 secs4882 Average loss: 0.4507
2.8751065731048584 secs1/4882 Average loss: 0.4679
2.9151995182037354 secs01/4882 Average loss: 0.4690
2.8890130519866943 secs01/4882 Average loss: 0.4690
2.8535759449005127 secs01/4882 Average loss: 0.4693
2.841226577758789 secs501/4882 Average loss: 0.4689
2.8082058429718018 secs01/4882 Average loss: 0.4697
2.8476266860961914 secs01/4882 Average loss: 0.4695
2.801241397857666 secs001/4882 Average loss: 0.4694
====> Epoch: 6 Average loss: 0.4691884073ss: 0.4694
Loss went from 0.4697 to 0.4692
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
0.5534849166870117 secs
2.9679901599884033 secs4882 Average loss: 0.4704
2.8405301570892334 secs1/4882 Average loss: 0.4686
2.8215978145599365 secs01/4882 Average loss: 0.4684
2.80216646194458 secs1501/4882 Average loss: 0.4689
2.8019914627075195 secs01/4882 Average loss: 0.4689
2.8815464973449707 secs01/4882 Average loss: 0.4692
2.8672516345977783 secs01/4882 Average loss: 0.4690
2.9466283321380615 secs01/4882 Average loss: 0.4690
2.8875198364257812 secs01/4882 Average loss: 0.4690
====> Epoch: 7 Average loss: 0.4689587733ss: 0.4690
Loss went from 0.4692 to 0.4690
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/utils/data/_utils/collate.py:285: UserWarning: The given NumPy array is not writable, and PyTorch does not support non-writable tensors. This means writing to this tensor will result in undefined behavior. You may want to copy the array to protect its data or make it writable before converting it to a tensor. This type of warning will be suppressed for the rest of this program. (Triggered internally at /pytorch/torch/csrc/utils/tensor_numpy.cpp:203.)
  return collate([torch.as_tensor(b) for b in batch], collate_fn_map=collate_fn_map)
0.5524234771728516 secs
2.9403553009033203 secs4882 Average loss: 0.4717
2.8596572875976562 secs1/4882 Average loss: 0.4673
2.961442708969116 secs001/4882 Average loss: 0.4685
2.8554224967956543 secs01/4882 Average loss: 0.4684
2.841087579727173 secs001/4882 Average loss: 0.4682
2.8475427627563477 secs01/4882 Average loss: 0.4685
2.887657880783081 secs001/4882 Average loss: 0.4686
2.8374202251434326 secs01/4882 Average loss: 0.4688
2.7953786849975586 secs01/4882 Average loss: 0.4688
====> Epoch: 8 Average loss: 0.4688564030ss: 0.4689
Loss went from 0.4690 to 0.4689
Done
Using MODEL_PATH for encoding
array type int64
/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/torch/optim/lr_scheduler.py:62: UserWarning: The verbose parameter is deprecated. Please use get_last_lr() to access the learning rate.
  warnings.warn(
156250
Traceback (most recent call last):
  File "/home/jx1421/Dzip-torch/coding-gpu/compress_adaptive.py", line 294, in <module>
    main()
  File "/home/jx1421/Dzip-torch/coding-gpu/compress_adaptive.py", line 254, in main
    compress(commodel, X, Y, batch_size, vocab_size, timesteps, device, optimizer, scheduler)
  File "/home/jx1421/Dzip-torch/coding-gpu/compress_adaptive.py", line 47, in compress
    enc[i].write(cumul, X[ind[i],j])
  File "/home/jx1421/Dzip-torch/coding-gpu/arithmeticcoding_fast.py", line 133, in write
    self.update(cumul, symbol)
  File "/home/jx1421/Dzip-torch/coding-gpu/arithmeticcoding_fast.py", line 79, in update
    total = np.asscalar(cumul[-1])
  File "/home/jx1421/Dzip-torch/torch_venv/lib64/python3.9/site-packages/numpy/__init__.py", line 410, in __getattr__
    raise AttributeError: "module {!r} has no attribute "
AttributeError: module 'numpy' has no attribute 'asscalar'
```