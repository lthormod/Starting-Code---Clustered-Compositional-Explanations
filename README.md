# Starting-Code---Clustered-Compositional-Explanations

# Input:
python3 scripts/run_clustering.py --subset=ade20k --model=resnet18 --pretrained=places365 --length=3 --beam_limit=5 --num_clusters=1 --device=cpu  --pre_load_masks=False --random_units=10 --root_models=data/model/ --root_datasets=data/dataset/ --root_segmentations=data/cache/segmentations/ --root_activations=data/cache/activations/ --root_results=data/results/ --seed=0

# Output with :
Loading model:resnet18
	from data/model/zoo/resnet18_places365.pth.tar
resnet18 loaded. Eval Modality
Loading Sparse Masks: 100%|████████████████| 1198/1198 [00:12<00:00, 97.90it/s]

Computing Compostional explanations per unit:   0%|     | 0/10 [00:00<?, ?it/s]Parsed Unit: 394 - Cluster: 0 - Best Label: ((attic-s OR tent) AND NOT floor) - Best IoU: 0.119 - Visited: 39

Computing Compostional explanations per unit:  10%| | 1/10 [07:37<1:08:35, 457.Parsed Unit: 430 - Cluster: 0 - Best Label: ((playroom-s OR kindergarden_classroom-s) OR day_care_center-s) - Best IoU: 0.111 - Visited: 9

Computing Compostional explanations per unit:  20%|▏| 2/10 [15:03<1:00:06, 450.^Parsed Unit: 41 - Cluster: 0 - Best Label: ((butchers_shop-s OR rubble-s) OR meat) - Best IoU: 0.069 - Visited: 33

Computing Compostional explanations per unit:  30%|▎| 3/10 [22:48<53:20, 457.18Parsed Unit: 265 - Cluster: 0 - Best Label: ((toilet OR cargo_container_interior-s) OR jail_cell-s) - Best IoU: 0.058 - Visited: 21

Computing Compostional explanations per unit:  40%|▍| 4/10 [30:22<45:36, 456.14Parsed Unit: 497 - Cluster: 0 - Best Label: ((cockpit-s OR bus_interior-s) OR airplane_cabin-s) - Best IoU: 0.169 - Visited: 11

Computing Compostional explanations per unit:  50%|▌| 5/10 [37:51<37:47, 453.54Parsed Unit: 414 - Cluster: 0 - Best Label: ((auditorium-s OR movie_theater-indoor-s) OR conference_center-s) - Best IoU: 0.105 - Visited: 10

Computing Compostional explanations per unit:  60%|▌| 6/10 [45:22<30:09, 452.43Parsed Unit: 310 - Cluster: 0 - Best Label: ((sink OR toilet) OR bathtub) - Best IoU: 0.207 - Visited: 20

Computing Compostional explanations per unit:  70%|▋| 7/10 [53:00<22:43, 454.41Parsed Unit: 488 - Cluster: 0 - Best Label: ((tent OR bandstand) OR canopy) - Best IoU: 0.107 - Visited: 14
Unit 41 - Cluster 0 - 
Computing Compostional explanations per unit:  80%|▊| 8/10 [1:00:32<15:07, 453.Parsed Unit: 366 - Cluster: 0 - Best Label: ((airport_terminal-s OR supermarket-s) AND NOT floor) - Best IoU: 0.058 - Visited: 27

Computing Compostional explanations per unit:  90%|▉| 9/10 [1:08:09<07:34, 454.^Parsed Unit: 223 - Cluster: 0 - Best Label: ((bowling_alley-s OR oast_house-s) OR cottage-s) - Best IoU: 0.066 - Visited: 39
Computing Compostional explanations per unit: 100%|█| 10/10 [1:15:49<00:00, 454


