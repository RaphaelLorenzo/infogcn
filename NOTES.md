Following : https://github.com/stnoah1/infogcn/issues/5

Used : python main.py --half=True --batch_size=32 --test_batch_size=64 --step 90 100 --num_epoch=110 --n_heads=3 --num_worker=4 --k=1 --dataset=ucla --num_class=10 --z_prior_gain=3 --use_vel=False --datacase=ucla --num_person=1 --num_point=20 --graph=graph.ucla.Graph --feeder=feeders.feeder_ucla.Feeder --lambda_1=1e-1 --lambda_2=1e-1 --base_lr 0.05 --weight_decay=4e-4

