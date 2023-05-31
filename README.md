# timm_speed_benchmark
Benchmarking the speed of timm models

# Hardware
GPU: RTX A6000

CPU: Ryzen 3600

# Results
Batchsize = 4.

|FIELD1                                                |fp32              |top1  |imsize|
|------------------------------------------------------|------------------|------|------|
|eva02_large_patch14_448.mim_m38m_ft_in22k_in1k        |171.2168550491333 |91.129|448.0 |
|eva_giant_patch14_336.clip_ft_in1k                    |166.4306116104126 |91.058|336.0 |
|eva02_large_patch14_448.mim_in22k_ft_in22k_in1k       |171.71310424804688|91.02 |448.0 |
|eva_giant_patch14_560.m30m_ft_in22k_in1k              |581.2683391571045 |90.969|560.0 |
|eva02_large_patch14_448.mim_in22k_ft_in1k             |172.71728515625   |90.922|448.0 |
|eva_giant_patch14_336.m30m_ft_in22k_in1k              |168.33984851837158|90.907|336.0 |
|eva_large_patch14_336.in22k_ft_in1k                   |63.14021587371826 |90.903|336.0 |
|eva_giant_patch14_224.clip_ft_in1k                    |77.15846538543701 |90.9  |224.0 |
|eva02_base_patch14_448.mim_in22k_ft_in22k_in1k        |64.20849800109863 |90.896|448.0 |
|eva02_large_patch14_448.mim_m38m_ft_in1k              |171.81569576263428|90.888|448.0 |
|eva_large_patch14_336.in22k_ft_in22k_in1k             |62.99717903137207 |90.862|336.0 |
|eva02_base_patch14_448.mim_in22k_ft_in1k              |64.43453788757324 |90.8  |448.0 |
|caformer_b36.sail_in22k_ft_in1k_384                   |69.94579792022705 |90.781|384.0 |
|beit_large_patch16_512.in22k_ft_in22k_in1k            |191.15906715393066|90.687|512.0 |
|convnext_large_mlp.clip_laion2b_soup_ft_in12k_in1k_384|42.12807655334473 |90.678|384.0 |
|regnety_1280.swag_ft_in1k                             |168.71695041656494|90.659|384.0 |
|convnext_xxlarge.clip_laion2b_soup_ft_in1k            |54.968552589416504|90.642|256.0 |
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384    |41.94615840911865 |90.633|384.0 |
|volo_d5_512.sail_in1k                                 |252.26200103759766|90.614|512.0 |
|beit_large_patch16_384.in22k_ft_in22k_in1k            |80.67306995391846 |90.606|384.0 |
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k              |80.75275897979736 |90.584|384.0 |
|volo_d5_448.sail_in1k                                 |181.4624261856079 |90.58 |448.0 |
|tf_efficientnet_l2.ns_jft_in1k                        |576.2402296066284 |90.561|800.0 |
|eva_large_patch14_196.in22k_ft_in22k_in1k             |20.766191482543945|90.555|196.0 |
|vit_large_patch14_clip_336.openai_ft_in12k_in1k       |63.34489822387695 |90.544|336.0 |
|convnextv2_huge.fcmae_ft_in22k_in1k_512               |208.26961517333984|90.542|512.0 |
|convnext_large_mlp.clip_laion2b_soup_ft_in12k_in1k_320|28.03785800933838 |90.54 |320.0 |
|tf_efficientnet_l2.ns_jft_in1k_475                    |230.43800830841064|90.537|475.0 |
|eva_large_patch14_196.in22k_ft_in1k                   |20.69573402404785 |90.533|196.0 |
|volo_d4_448.sail_in1k                                 |126.32205486297607|90.512|448.0 |
|vit_huge_patch14_clip_336.laion2b_ft_in12k_in1k       |117.63307094573975|90.501|336.0 |
|convnextv2_huge.fcmae_ft_in22k_in1k_384               |119.21083927154541|90.497|384.0 |
|convnext_xlarge.fb_in22k_ft_in1k_384                  |56.667842864990234|90.495|384.0 |
|caformer_m36.sail_in22k_ft_in1k_384                   |52.81733512878418 |90.458|384.0 |
|convformer_b36.sail_in22k_ft_in1k_384                 |63.89447212219238 |90.448|384.0 |
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k           |120.13701438903809|90.444|384.0 |
|caformer_b36.sail_in22k_ft_in1k                       |23.295392990112305|90.431|224.0 |
|vit_large_patch14_clip_336.laion2b_ft_in12k_in1k      |63.05959224700928 |90.428|336.0 |
|vit_huge_patch14_clip_224.laion2b_ft_in12k_in1k       |53.60339164733887 |90.418|224.0 |
|swinv2_base_window12to24_192to384.ms_in22k_ft_in1k    |75.2923583984375  |90.407|384.0 |
|vit_large_patch14_clip_224.openai_ft_in12k_in1k       |26.922550201416016|90.379|224.0 |
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k                |54.370665550231934|90.377|384.0 |
|beit_base_patch16_384.in22k_ft_in22k_in1k             |31.253252029418945|90.367|384.0 |
|convnextv2_large.fcmae_ft_in22k_in1k_384              |56.44268989562988 |90.367|384.0 |
|convnextv2_base.fcmae_ft_in22k_in1k_384               |35.88428974151611 |90.36 |384.0 |
|beitv2_large_patch16_224.in1k_ft_in22k_in1k           |22.39323616027832 |90.354|224.0 |
|vit_large_patch14_clip_336.laion2b_ft_in1k            |62.644171714782715|90.332|336.0 |
|convnext_base.clip_laion2b_augreg_ft_in12k_in1k_384   |25.72718620300293 |90.33 |384.0 |
|vit_large_patch14_clip_224.laion2b_ft_in12k_in1k      |26.761474609375   |90.311|224.0 |
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k        |18.87547016143799 |90.309|256.0 |
|vit_large_patch14_clip_224.openai_ft_in1k             |26.78530216217041 |90.309|224.0 |
|caformer_s36.sail_in22k_ft_in1k_384                   |41.20553493499756 |90.305|384.0 |
|convnext_base.fb_in22k_ft_in1k_384                    |25.742578506469727|90.283|384.0 |
|convnext_large.fb_in22k_ft_in1k_384                   |41.74063682556152 |90.279|384.0 |
|deit3_large_patch16_384.fb_in22k_ft_in1k              |64.4304370880127  |90.247|384.0 |
|dm_nfnet_f6.dm_in1k                                   |261.2537479400635 |90.241|576.0 |
|seresnextaa101d_32x8d.sw_in12k_ft_in1k_288            |33.421077728271484|90.226|320.0 |
|deit3_huge_patch14_224.fb_in22k_ft_in1k               |54.67087268829346 |90.226|224.0 |
|regnety_320.swag_ft_in1k                              |51.15824222564697 |90.219|384.0 |
|vit_base_patch16_clip_384.laion2b_ft_in1k             |24.795684814453125|90.213|384.0 |
|vit_large_patch16_384.augreg_in21k_ft_in1k            |63.250885009765625|90.213|384.0 |
|convformer_m36.sail_in22k_ft_in1k_384                 |48.76349925994873 |90.204|384.0 |
|convnextv2_huge.fcmae_ft_in1k                         |71.82510375976562 |90.204|288.0 |
|tf_efficientnetv2_l.in21k_ft_in1k                     |54.7554349899292  |90.202|480.0 |
|vit_base_patch16_clip_384.openai_ft_in12k_in1k        |24.799633026123047|90.2  |384.0 |
|convformer_b36.sail_in22k_ft_in1k                     |27.095818519592285|90.189|224.0 |
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k       |24.79379653930664 |90.189|384.0 |
|cait_m48_448.fb_dist_in1k                             |485.3704833984375 |90.189|448.0 |
|vit_huge_patch14_clip_224.laion2b_ft_in1k             |54.03954029083252 |90.181|224.0 |
|volo_d3_448.sail_in1k                                 |94.85130310058594 |90.174|448.0 |
|swinv2_large_window12to24_192to384.ms_in22k_ft_in1k   |114.09129619598389|90.157|384.0 |
|beit_large_patch16_224.in22k_ft_in22k_in1k            |22.73066520690918 |90.149|224.0 |
|beitv2_large_patch16_224.in1k_ft_in1k                 |22.65066146850586 |90.1  |224.0 |
|tf_efficientnet_b7.ns_jft_in1k                        |81.2997817993164  |90.098|600.0 |
|vit_large_patch14_clip_224.laion2b_ft_in1k            |27.08686351776123 |90.098|224.0 |
|convnextv2_base.fcmae_ft_in22k_in1k                   |21.859440803527832|90.068|288.0 |
|convnext_xlarge.fb_in22k_ft_in1k                      |36.38938903808594 |90.066|288.0 |
|caformer_b36.sail_in1k_384                            |69.72106456756592 |90.063|384.0 |
|cait_m36_384.fb_dist_in1k                             |209.58524227142334|90.051|384.0 |
|convnextv2_large.fcmae_ft_in22k_in1k                  |33.177433013916016|90.034|288.0 |
|seresnextaa101d_32x8d.sw_in12k_ft_in1k                |29.057912826538086|90.029|288.0 |
|tf_efficientnetv2_m.in21k_ft_in1k                     |30.637574195861816|90.023|480.0 |
|convformer_s36.sail_in22k_ft_in1k_384                 |37.4086332321167  |90.023|384.0 |
|swin_large_patch4_window12_384.ms_in22k_ft_in1k       |57.90896415710449 |90.019|384.0 |
|deit3_large_patch16_224.fb_in22k_ft_in1k              |21.118860244750977|90.008|224.0 |
|convnext_base.clip_laiona_augreg_ft_in1k_384          |25.838193893432617|90.001|384.0 |
|swin_base_patch4_window12_384.ms_in22k_ft_in1k        |37.124857902526855|89.997|384.0 |
|vit_base_patch16_384.augreg_in21k_ft_in1k             |24.75289821624756 |89.989|384.0 |
|caformer_m36.sail_in1k_384                            |52.869019508361816|89.933|384.0 |
|convnextv2_large.fcmae_ft_in1k                        |33.02581787109375 |89.931|288.0 |
|maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k              |38.51691246032715 |89.927|224.0 |
|swinv2_large_window12to16_192to256.ms_in22k_ft_in1k   |34.15823459625244 |89.925|256.0 |
|regnety_160.swag_ft_in1k                              |30.883865356445312|89.918|384.0 |
|convnext_small.fb_in22k_ft_in1k_384                   |18.99101734161377 |89.916|384.0 |
|efficientnet_b5.sw_in12k_ft_in1k                      |26.90467357635498 |89.91 |448.0 |
|deit3_base_patch16_384.fb_in22k_ft_in1k               |25.240039825439453|89.891|384.0 |
|xcit_large_24_p8_384.fb_dist_in1k                     |173.2826852798462 |89.886|384.0 |
|volo_d5_224.sail_in1k                                 |36.49049758911133 |89.88 |224.0 |
|convnext_large.fb_in22k_ft_in1k                       |24.340882301330566|89.876|288.0 |
|swinv2_base_window12to16_192to256.ms_in22k_ft_in1k    |22.624244689941406|89.867|256.0 |
|convnext_base.fb_in22k_ft_in1k                        |15.66577434539795 |89.858|288.0 |
|caformer_m36.sail_in22k_ft_in1k                       |17.474775314331055|89.854|224.0 |
|cait_s36_384.fb_dist_in1k                             |101.8310022354126 |89.835|384.0 |
|coatnet_2_rw_224.sw_in12k_ft_in1k                     |18.44301700592041 |89.831|224.0 |
|convformer_m36.sail_in22k_ft_in1k                     |19.892358779907227|89.818|224.0 |
|xcit_medium_24_p8_384.fb_dist_in1k                    |108.35433959960938|89.816|384.0 |
|convnext_base.clip_laion2b_augreg_ft_in12k_in1k       |11.771078109741211|89.811|256.0 |
|volo_d4_224.sail_in1k                                 |24.9357271194458  |89.811|224.0 |
|vit_large_r50_s32_384.augreg_in21k_ft_in1k            |29.021129608154297|89.792|384.0 |
|volo_d2_384.sail_in1k                                 |42.049713134765625|89.788|384.0 |
|swin_large_patch4_window7_224.ms_in22k_ft_in1k        |18.594460487365723|89.786|224.0 |
|tf_efficientnet_b6.ns_jft_in1k                        |48.62365245819092 |89.782|528.0 |
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k                |18.89118194580078 |89.775|224.0 |
|tf_efficientnetv2_xl.in21k_ft_in1k                    |84.6269702911377  |89.771|512.0 |
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k           |79.76803302764893 |89.752|224.0 |
|beitv2_base_patch16_224.in1k_ft_in22k_in1k            |7.904720306396484 |89.743|224.0 |
|dm_nfnet_f5.dm_in1k                                   |211.79538249969482|89.741|544.0 |
|dm_nfnet_f4.dm_in1k                                   |161.23919010162354|89.737|512.0 |
|xcit_small_24_p8_384.fb_dist_in1k                     |80.67288875579834 |89.735|384.0 |
|regnety_160.lion_in12k_ft_in1k                        |21.250972747802734|89.724|288.0 |
|caformer_s18.sail_in22k_ft_in1k_384                   |22.870726585388184|89.72 |384.0 |
|vit_base_patch8_224.augreg2_in21k_ft_in1k             |35.424509048461914|89.718|224.0 |
|convformer_m36.sail_in1k_384                          |48.889498710632324|89.718|384.0 |
|vit_base_patch16_clip_384.openai_ft_in1k              |24.94328022003174 |89.707|384.0 |
|caformer_s36.sail_in22k_ft_in1k                       |16.176657676696777|89.701|224.0 |
|volo_d1_384.sail_in1k                                 |24.760408401489258|89.698|384.0 |
|deit3_large_patch16_384.fb_in1k                       |64.88831520080566 |89.688|384.0 |
|caformer_s36.sail_in1k_384                            |41.4231538772583  |89.679|384.0 |
|xcit_large_24_p16_384.fb_dist_in1k                    |50.99280834197998 |89.662|384.0 |
|convformer_b36.sail_in1k_384                          |64.12924766540527 |89.658|384.0 |
|tf_efficientnet_b5.ns_jft_in1k                        |29.551067352294922|89.651|456.0 |
|dm_nfnet_f3.dm_in1k                                   |97.38987445831299 |89.647|416.0 |
|convnext_base.clip_laion2b_augreg_ft_in1k             |11.782488822937012|89.645|256.0 |
|regnety_2560.seer_ft_in1k                             |272.9004383087158 |89.632|384.0 |
|convnext_small.in12k_ft_in1k_384                      |19.088926315307617|89.598|384.0 |
|tf_efficientnet_b8.ap_in1k                            |122.60839939117432|89.579|672.0 |
|regnety_160.sw_in12k_ft_in1k                          |21.192007064819336|89.57 |288.0 |
|vit_base_patch16_clip_224.laion2b_ft_in12k_in1k       |7.2327375411987305|89.564|224.0 |
|convformer_s18.sail_in22k_ft_in1k_384                 |21.111130714416504|89.553|384.0 |
|volo_d3_224.sail_in1k                                 |17.56282329559326 |89.553|224.0 |
|tf_efficientnetv2_l.in1k                              |54.75166320800781 |89.54 |480.0 |
|flexivit_large.1200ep_in1k                            |24.442949295043945|89.534|240.0 |
|xcit_large_24_p8_224.fb_dist_in1k                     |69.5625114440918  |89.517|224.0 |
|flexivit_large.600ep_in1k                             |24.433903694152832|89.508|240.0 |
|xcit_small_12_p8_384.fb_dist_in1k                     |42.785401344299316|89.508|384.0 |
|cait_s24_384.fb_dist_in1k                             |68.5398530960083  |89.504|384.0 |
|convformer_s36.sail_in22k_ft_in1k                     |18.201823234558105|89.496|224.0 |
|convnextv2_tiny.fcmae_ft_in22k_in1k_384               |17.601213455200195|89.485|384.0 |
|convformer_s36.sail_in1k_384                          |37.34050750732422 |89.481|384.0 |
|xcit_medium_24_p16_384.fb_dist_in1k                   |32.19667911529541 |89.481|384.0 |
|convnext_tiny.in12k_ft_in1k_384                       |12.764992713928223|89.472|384.0 |
|deit3_base_patch16_224.fb_in22k_ft_in1k               |7.408466339111328 |89.446|224.0 |
|vit_base_patch16_224.augreg2_in21k_ft_in1k            |7.2542619705200195|89.444|224.0 |
|vit_base_patch32_clip_448.laion2b_ft_in12k_in1k       |8.94580364227295  |89.44 |448.0 |
|regnety_120.sw_in12k_ft_in1k                          |17.249088287353516|89.436|288.0 |
|vit_base_patch8_224.augreg_in21k_ft_in1k              |35.202903747558594|89.436|224.0 |
|deit_base_distilled_patch16_384.fb_in1k               |24.72419261932373 |89.434|384.0 |
|tf_efficientnet_b7.ap_in1k                            |81.04320049285889 |89.429|600.0 |
|vit_base_patch16_clip_224.laion2b_ft_in1k             |7.197971343994141 |89.427|224.0 |
|convnextv2_base.fcmae_ft_in1k                         |21.80408477783203 |89.421|288.0 |
|caformer_b36.sail_in1k                                |23.217487335205078|89.41 |224.0 |
|vit_base_patch16_clip_224.openai_ft_in12k_in1k        |7.255816459655762 |89.401|224.0 |
|hrnet_w48_ssld.paddle_in1k                            |32.19280242919922 |89.401|288.0 |
|beit_base_patch16_224.in22k_ft_in22k_in1k             |7.8772735595703125|89.395|224.0 |
|regnetz_e8.ra3_in1k                                   |29.124879837036133|89.378|320.0 |
|deit3_small_patch16_384.fb_in22k_ft_in1k              |11.160078048706055|89.363|384.0 |
|vit_medium_patch16_gap_384.sw_in12k_ft_in1k           |15.053777694702148|89.348|384.0 |
|tf_efficientnetv2_m.in1k                              |30.609455108642578|89.348|480.0 |
|tf_efficientnet_b8.ra_in1k                            |122.40338802337646|89.348|672.0 |
|tf_efficientnet_b6.ap_in1k                            |48.698787689208984|89.344|528.0 |
|volo_d2_224.sail_in1k                                 |12.503161430358887|89.335|224.0 |
|caformer_s18.sail_in1k_384                            |22.83780574798584 |89.331|384.0 |
|eva02_small_patch14_336.mim_in22k_ft_in1k             |13.184804916381836|89.327|336.0 |
|vit_large_patch16_224.augreg_in21k_ft_in1k            |20.69068431854248 |89.318|224.0 |
|flexivit_large.300ep_in1k                             |24.44446563720703 |89.305|240.0 |
|tf_efficientnet_b4.ns_jft_in1k                        |16.13293170928955 |89.301|380.0 |
|convnext_small.fb_in22k_ft_in1k                       |11.204524040222168|89.299|288.0 |
|xcit_small_24_p16_384.fb_dist_in1k                    |23.186001777648926|89.295|384.0 |
|xcit_medium_24_p8_224.fb_dist_in1k                    |43.39779853820801 |89.293|224.0 |
|beitv2_base_patch16_224.in1k_ft_in1k                  |7.904620170593262 |89.271|224.0 |
|deit3_huge_patch14_224.fb_in1k                        |54.60422992706299 |89.218|224.0 |
|coat_lite_medium_384.in1k                             |36.5740442276001  |89.209|384.0 |
|xcit_small_24_p8_224.fb_dist_in1k                     |29.130005836486816|89.199|224.0 |
|xcit_small_12_p16_384.fb_dist_in1k                    |13.527212142944336|89.197|384.0 |
|vit_base_patch32_clip_384.laion2b_ft_in12k_in1k       |7.342848777770996 |89.194|384.0 |
|dm_nfnet_f2.dm_in1k                                   |59.428324699401855|89.192|352.0 |
|swin_base_patch4_window7_224.ms_in22k_ft_in1k         |12.82036304473877 |89.173|224.0 |
|vit_base_patch16_clip_224.openai_ft_in1k              |7.216582298278809 |89.167|224.0 |
|eca_nfnet_l2.ra3_in1k                                 |37.229371070861816|89.147|384.0 |
|cait_xs24_384.fb_dist_in1k                            |49.75600242614746 |89.147|384.0 |
|convformer_s18.sail_in1k_384                          |21.09790325164795 |89.124|384.0 |
|resnext101_32x32d.fb_wsl_ig1b_ft_in1k                 |67.65288352966309 |89.107|224.0 |
|tf_efficientnet_b7.ra_in1k                            |81.0150957107544  |89.083|600.0 |
|ecaresnet269d.ra2_in1k                                |40.4368257522583  |89.073|352.0 |
|regnety_1280.seer_ft_in1k                             |168.409686088562  |89.064|384.0 |
|vit_base_patch32_clip_384.openai_ft_in12k_in1k        |7.444438934326172 |89.051|384.0 |
|xcit_large_24_p16_224.fb_dist_in1k                    |18.431344032287598|89.045|224.0 |
|convnext_small.in12k_ft_in1k                          |11.193723678588867|89.024|288.0 |
|dm_nfnet_f1.dm_in1k                                   |35.44049263000488 |89.019|320.0 |
|resmlp_big_24_224.fb_in22k_ft_in1k                    |34.073710441589355|89.019|224.0 |
|xcit_small_12_p8_224.fb_dist_in1k                     |15.74880599975586 |89.011|224.0 |
|convnext_large.fb_in1k                                |24.32772159576416 |88.994|288.0 |
|caformer_m36.sail_in1k                                |17.432398796081543|88.99 |224.0 |
|efficientnetv2_rw_m.agc_in1k                          |27.33175754547119 |88.987|416.0 |
|regnety_1280.swag_lc_in1k                             |70.75120449066162 |88.951|224.0 |
|regnetz_d8_evos.ch_in1k                               |31.721558570861816|88.951|320.0 |
|regnetz_040_h.ra3_in1k                                |16.975302696228027|88.949|320.0 |
|edgenext_base.in21k_ft_in1k                           |78.00333023071289 |88.942|320.0 |
|tf_efficientnet_b5.ap_in1k                            |29.445910453796387|88.94 |456.0 |
|mvitv2_large.fb_in1k                                  |49.111666679382324|88.936|224.0 |
|caformer_s18.sail_in22k_ft_in1k                       |9.181790351867676 |88.932|224.0 |
|deit3_base_patch16_384.fb_in1k                        |25.33609390258789 |88.923|384.0 |
|deit3_medium_patch16_224.fb_in22k_ft_in1k             |5.5593109130859375|88.921|224.0 |
|volo_d1_224.sail_in1k                                 |9.429736137390137 |88.915|224.0 |
|convnext_tiny.in12k_ft_in1k                           |7.422780990600586 |88.906|288.0 |
|tf_efficientnetv2_s.in21k_ft_in1k                     |16.528091430664062|88.898|384.0 |
|vit_base_patch16_224.augreg_in21k_ft_in1k             |7.22592830657959  |88.87 |224.0 |
|convnext_tiny.fb_in22k_ft_in1k_384                    |12.775044441223145|88.855|384.0 |
|regnetz_d8.ra3_in1k                                   |15.848784446716309|88.853|320.0 |
|convformer_b36.sail_in1k                              |27.05242156982422 |88.851|224.0 |
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k               |15.46870231628418 |88.842|224.0 |
|resnetrs420.tf_in1k                                   |93.55855941772461 |88.838|416.0 |
|resnext101_32x16d.fb_wsl_ig1b_ft_in1k                 |30.859827995300293|88.834|224.0 |
|resnetrs270.tf_in1k                                   |46.121697425842285|88.829|352.0 |
|vit_small_r26_s32_384.augreg_in21k_ft_in1k            |11.600751876831055|88.817|384.0 |
|swin_small_patch4_window7_224.ms_in22k_ft_in1k        |12.54335880279541 |88.817|224.0 |
|vit_base_r50_s16_384.orig_in21k_ft_in1k               |36.59476280212402 |88.806|384.0 |
|xcit_medium_24_p16_224.fb_dist_in1k                   |18.222661018371582|88.806|224.0 |
|tf_efficientnet_b7.aa_in1k                            |81.05557918548584 |88.804|600.0 |
|maxxvit_rmlp_small_rw_256.sw_in1k                     |61.75087928771973 |88.795|256.0 |
|seresnet152d.ra2_in1k                                 |24.485087394714355|88.787|320.0 |
|xcit_tiny_24_p8_384.fb_dist_in1k                      |43.99637699127197 |88.787|384.0 |
|convformer_m36.sail_in1k                              |19.98155117034912 |88.787|224.0 |
|resnext101_32x8d.fb_swsl_ig1b_ft_in1k                 |17.562475204467773|88.782|224.0 |
|resnetrs200.tf_in1k                                   |32.33295917510986 |88.763|320.0 |
|convnext_base.fb_in1k                                 |15.703659057617188|88.763|288.0 |
|deit3_large_patch16_224.fb_in1k                       |21.117572784423828|88.763|224.0 |
|tf_efficientnet_b6.aa_in1k                            |48.68879318237305 |88.759|528.0 |
|resnetrs350.tf_in1k                                   |65.29199123382568 |88.757|384.0 |
|rexnetr_300.sw_in12k_ft_in1k                          |10.839242935180664|88.746|288.0 |
|caformer_s36.sail_in1k                                |17.016444206237793|88.746|224.0 |
|convnextv2_tiny.fcmae_ft_in22k_in1k                   |10.33353328704834 |88.744|288.0 |
|vit_base_patch16_224_miil.in21k_ft_in1k               |7.078952789306641 |88.74 |224.0 |
|edgenext_base.usi_in1k                                |78.02728652954102 |88.735|320.0 |
|regnetz_040.ra3_in1k                                  |16.674165725708008|88.731|320.0 |
|convformer_s18.sail_in22k_ft_in1k                     |9.89673137664795  |88.727|224.0 |
|resnetv2_152x2_bit.goog_in21k_ft_in1k                 |93.25749397277832 |88.725|448.0 |
|regnety_160.deit_in1k                                 |21.190643310546875|88.703|288.0 |
|davit_base.msft_in1k                                  |13.799924850463867|88.701|224.0 |
|regnety_640.seer_ft_in1k                              |85.89212894439697 |88.674|384.0 |
|vit_small_patch16_384.augreg_in21k_ft_in1k            |11.35932445526123 |88.652|384.0 |
|regnetz_d32.ra3_in1k                                  |15.807938575744629|88.652|320.0 |
|flexivit_base.1200ep_in1k                             |8.583693504333496 |88.648|240.0 |
|mvitv2_base.fb_in1k                                   |21.49949073791504 |88.644|224.0 |
|regnety_080.ra3_in1k                                  |14.379606246948242|88.635|288.0 |
|vit_medium_patch16_gap_256.sw_in12k_ft_in1k           |6.27321720123291  |88.633|256.0 |
|davit_small.msft_in1k                                 |14.422059059143066|88.631|224.0 |
|eca_nfnet_l1.ra2_in1k                                 |20.871601104736328|88.624|320.0 |
|swinv2_base_window16_256.ms_in1k                      |22.609152793884277|88.586|256.0 |
|regnety_320.seer_ft_in1k                              |51.200881004333496|88.573|384.0 |
|resnetaa101d.sw_in12k_ft_in1k                         |11.710457801818848|88.573|288.0 |
|resnetv2_152x4_bit.goog_in21k_ft_in1k                 |278.053879737854  |88.554|480.0 |
|resnet200d.ra2_in1k                                   |24.506206512451172|88.554|320.0 |
|xcit_small_24_p16_224.fb_dist_in1k                    |18.113980293273926|88.545|224.0 |
|flexivit_base.600ep_in1k                              |8.539323806762695 |88.545|240.0 |
|seresnextaa101d_32x8d.ah_in1k                         |28.998165130615234|88.537|288.0 |
|maxvit_rmlp_small_rw_224.sw_in1k                      |18.32876205444336 |88.522|224.0 |
|resnest269e.in1k                                      |78.8521957397461  |88.52 |416.0 |
|coatnet_rmlp_2_rw_224.sw_in1k                         |18.957457542419434|88.513|224.0 |
|efficientformerv2_l.snap_dist_in1k                    |19.194693565368652|88.507|224.0 |
|gcvit_base.in1k                                       |19.243192672729492|88.501|224.0 |
|swinv2_base_window8_256.ms_in1k                       |17.120323181152344|88.498|256.0 |
|seresnext101_32x8d.ah_in1k                            |27.62331485748291 |88.494|288.0 |
|convformer_s36.sail_in1k                              |18.58560085296631 |88.486|224.0 |
|crossvit_18_dagger_408.in1k                           |25.42459487915039 |88.479|408.0 |
|flexivit_base.300ep_in1k                              |8.547534942626953 |88.479|240.0 |
|efficientnetv2_rw_s.ra2_in1k                          |16.22281551361084 |88.475|384.0 |
|resnetv2_101x3_bit.goog_in21k_ft_in1k                 |113.1847620010376 |88.466|448.0 |
|resnetv2_50x3_bit.goog_in21k_ft_in1k                  |66.58966541290283 |88.447|448.0 |
|cait_s24_224.fb_dist_in1k                             |13.393187522888184|88.443|224.0 |
|resmlp_big_24_224.fb_distilled_in1k                   |34.00523662567139 |88.441|224.0 |
|regnetv_064.ra3_in1k                                  |14.404621124267578|88.439|288.0 |
|resnest200e.in1k                                      |38.89949321746826 |88.434|320.0 |
|vit_large_r50_s32_224.augreg_in21k_ft_in1k            |17.686762809753418|88.43 |224.0 |
|tf_efficientnet_b3.ns_jft_in1k                        |11.055431365966797|88.428|300.0 |
|seresnext101d_32x8d.ah_in1k                           |28.04253101348877 |88.428|288.0 |
|swin_base_patch4_window12_384.ms_in1k                 |37.11139678955078 |88.426|384.0 |
|tf_efficientnetv2_s.in1k                              |16.368160247802734|88.409|384.0 |
|convnext_small.fb_in1k                                |11.182708740234375|88.407|288.0 |
|tf_efficientnet_b5.aa_in1k                            |29.45002555847168 |88.407|456.0 |
|regnety_320.swag_lc_in1k                              |19.843921661376953|88.398|224.0 |
|vit_base_patch16_384.orig_in21k_ft_in1k               |24.669289588928223|88.389|384.0 |
|regnetz_c16_evos.ch_in1k                              |22.7862548828125  |88.381|320.0 |
|tresnet_v2_l.miil_in21k_ft_in1k                       |16.637301445007324|88.379|224.0 |
|swinv2_small_window16_256.ms_in1k                     |17.490501403808594|88.372|256.0 |
|efficientnet_b4.ra2_in1k                              |15.33318042755127 |88.366|384.0 |
|resnet152d.ra2_in1k                                   |18.206281661987305|88.362|320.0 |
|maxvit_rmlp_tiny_rw_256.sw_in1k                       |18.98764133453369 |88.355|256.0 |
|tf_efficientnet_b4.ap_in1k                            |16.214075088500977|88.347|380.0 |
|deit3_small_patch16_224.fb_in22k_ft_in1k              |5.699458122253418 |88.336|224.0 |
|regnety_064.ra3_in1k                                  |15.553078651428223|88.323|288.0 |
|convnextv2_nano.fcmae_ft_in22k_in1k_384               |14.21870231628418 |88.315|384.0 |
|crossvit_15_dagger_408.in1k                           |19.35037612915039 |88.313|408.0 |
|tf_efficientnet_b5.ra_in1k                            |29.420838356018066|88.308|456.0 |
|cs3se_edgenet_x.c2ns_in1k                             |12.478575706481934|88.296|320.0 |
|deit3_small_patch16_384.fb_in1k                       |11.395392417907715|88.296|384.0 |
|pvt_v2_b4.in1k                                        |23.757519721984863|88.285|224.0 |
|efficientformer_l7.snap_dist_in1k                     |12.846636772155762|88.278|224.0 |
|mvitv2_small.fb_in1k                                  |14.775328636169434|88.264|224.0 |
|resnetrs152.tf_in1k                                   |24.564685821533203|88.249|320.0 |
|deit3_base_patch16_224.fb_in1k                        |7.398672103881836 |88.244|224.0 |
|xcit_small_12_p16_224.fb_dist_in1k                    |10.543160438537598|88.24 |224.0 |
|gcvit_small.in1k                                      |18.46127986907959 |88.217|224.0 |
|regnetv_040.ra3_in1k                                  |13.429698944091797|88.212|288.0 |
|deit_base_distilled_patch16_224.fb_in1k               |7.23637580871582  |88.212|224.0 |
|xception65p.ra3_in1k                                  |12.524986267089844|88.189|299.0 |
|swinv2_small_window8_256.ms_in1k                      |17.18367099761963 |88.172|256.0 |
|caformer_s18.sail_in1k                                |8.954010009765625 |88.163|224.0 |
|xcit_tiny_24_p16_384.fb_dist_in1k                     |19.14804458618164 |88.161|384.0 |
|xcit_large_24_p8_224.fb_in1k                          |69.32458877563477 |88.161|224.0 |
|resnetv2_152x2_bit.goog_teacher_in21k_ft_in1k_384     |69.00438785552979 |88.153|384.0 |
|coat_lite_medium.in1k                                 |38.21368217468262 |88.144|224.0 |
|resnext101_32x8d.fb_wsl_ig1b_ft_in1k                  |17.57148265838623 |88.144|224.0 |
|cait_xxs36_384.fb_dist_in1k                           |48.83590221405029 |88.14 |384.0 |
|dm_nfnet_f0.dm_in1k                                   |15.056757926940918|88.131|256.0 |
|resnext101_32x4d.fb_swsl_ig1b_ft_in1k                 |12.854657173156738|88.112|224.0 |
|pit_b_distilled_224.in1k                              |53.52402687072754 |88.108|224.0 |
|xcit_tiny_12_p8_384.fb_dist_in1k                      |23.698225021362305|88.103|384.0 |
|pvt_v2_b5.in1k                                        |29.53524112701416 |88.103|224.0 |
|pvt_v2_b3.in1k                                        |16.357274055480957|88.099|224.0 |
|rexnetr_200.sw_in12k_ft_in1k                          |8.307509422302246 |88.097|288.0 |
|xception65.ra3_in1k                                   |13.9369535446167  |88.069|299.0 |
|hrnet_w18_ssld.paddle_in1k                            |30.883126258850098|88.067|288.0 |
|swin_s3_base_224.ms_in1k                              |16.790380477905273|88.046|224.0 |
|xcit_tiny_24_p8_224.fb_dist_in1k                      |17.71733283996582 |88.037|224.0 |
|convnextv2_tiny.fcmae_ft_in1k                         |10.269174575805664|88.035|288.0 |
|resnet152.a1h_in1k                                    |16.412534713745117|88.033|288.0 |
|focalnet_base_srf.ms_in1k                             |18.08976173400879 |88.033|224.0 |
|regnety_160.swag_lc_in1k                              |15.582146644592285|88.031|224.0 |
|focalnet_base_lrf.ms_in1k                             |18.808999061584473|88.003|224.0 |
|gcvit_tiny.in1k                                       |20.645732879638672|88.001|224.0 |
|eca_nfnet_l0.ra2_in1k                                 |11.31533145904541 |87.98 |288.0 |
|tf_efficientnet_b5.in1k                               |29.41244602203369 |87.973|456.0 |
|cs3sedarknet_x.c2ns_in1k                              |11.795220375061035|87.973|288.0 |
|nfnet_l0.ra2_in1k                                     |12.119746208190918|87.969|288.0 |
|efficientformer_l3.snap_dist_in1k                     |9.555997848510742 |87.963|224.0 |
|xcit_small_24_p8_224.fb_in1k                          |29.114890098571777|87.956|224.0 |
|tf_efficientnet_b4.aa_in1k                            |15.79012393951416 |87.954|380.0 |
|regnetz_c16.ra3_in1k                                  |15.2811861038208  |87.952|320.0 |
|regnety_032.ra_in1k                                   |12.852754592895508|87.945|288.0 |
|coatnet_1_rw_224.sw_in1k                              |13.888168334960938|87.943|224.0 |
|resnet101d.ra2_in1k                                   |13.180484771728516|87.935|320.0 |
|regnety_040.ra3_in1k                                  |14.017930030822754|87.933|288.0 |
|mobilevitv2_200.cvnets_in22k_ft_in1k_384              |21.093859672546387|87.933|384.0 |
|swinv2_cr_small_ns_224.sw_in1k                        |15.435771942138672|87.933|224.0 |
|focalnet_small_lrf.ms_in1k                            |18.27385902404785 |87.93 |224.0 |
|resnetv2_101.a1h_in1k                                 |12.128839492797852|87.924|288.0 |
|vit_base_patch32_384.augreg_in21k_ft_in1k             |7.543940544128418 |87.909|384.0 |
|sequencer2d_l.in1k                                    |39.024906158447266|87.907|224.0 |
|twins_svt_large.in1k                                  |12.806124687194824|87.903|224.0 |
|coatnet_rmlp_1_rw_224.sw_in1k                         |15.86172103881836 |87.892|224.0 |
|swin_base_patch4_window7_224.ms_in1k                  |12.765655517578125|87.866|224.0 |
|twins_pcpvt_large.in1k                                |21.23004913330078 |87.864|224.0 |
|maxvit_tiny_rw_224.sw_in1k                            |16.030526161193848|87.856|224.0 |
|swin_s3_small_224.ms_in1k                             |11.990461349487305|87.849|224.0 |
|convformer_s18.sail_in1k                              |9.40216064453125  |87.845|224.0 |
|mobilevitv2_175.cvnets_in22k_ft_in1k_384              |18.890366554260254|87.841|384.0 |
|deit_base_patch16_384.fb_in1k                         |24.64806079864502 |87.841|384.0 |
|ecaresnet101d.miil_in1k                               |14.488749504089355|87.839|288.0 |
|convnext_nano.in12k_ft_in1k                           |6.944174766540527 |87.837|288.0 |
|xcit_small_12_p8_224.fb_in1k                          |15.665831565856934|87.822|224.0 |
|flexivit_small.1200ep_in1k                            |5.361123085021973 |87.813|240.0 |
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k       |5.142560005187988 |87.809|224.0 |
|focalnet_small_srf.ms_in1k                            |16.491999626159668|87.809|224.0 |
|maxxvit_rmlp_nano_rw_256.sw_in1k                      |38.12272548675537 |87.807|256.0 |
|flexivit_small.600ep_in1k                             |5.540552139282227 |87.807|240.0 |
|tf_efficientnetv2_b3.in21k_ft_in1k                    |12.637019157409668|87.805|300.0 |
|deit3_medium_patch16_224.fb_in1k                      |5.526890754699707 |87.802|224.0 |
|tresnet_xl.miil_in1k_448                              |34.687628746032715|87.798|448.0 |
|resnetv2_50x1_bit.goog_distilled_in1k                 |8.744587898254395 |87.792|224.0 |
|convnext_tiny.fb_in1k                                 |7.454419136047363 |87.77 |288.0 |
|regnety_320.tv2_in1k                                  |19.827299118041992|87.743|224.0 |
|resnext101_64x4d.tv_in1k                              |17.699899673461914|87.74 |224.0 |
|convnextv2_nano.fcmae_ft_in22k_in1k                   |8.860068321228027 |87.732|288.0 |
|twins_pcpvt_base.in1k                                 |15.149860382080078|87.73 |224.0 |
|tresnet_m.miil_in21k_ft_in1k                          |10.108418464660645|87.723|224.0 |
|gc_efficientnetv2_rw_t.agc_in1k                       |19.25772190093994 |87.719|288.0 |
|mvitv2_tiny.fb_in1k                                   |9.835329055786133 |87.719|224.0 |
|maxvit_rmlp_nano_rw_256.sw_in1k                       |12.54331111907959 |87.715|256.0 |
|resnetv2_101x1_bit.goog_in21k_ft_in1k                 |26.33981704711914 |87.683|448.0 |
|rexnet_300.nav_in1k                                   |8.3121919631958   |87.683|224.0 |
|swin_small_patch4_window7_224.ms_in1k                 |12.398390769958496|87.662|224.0 |
|efficientnetv2_rw_t.ra2_in1k                          |14.4537353515625  |87.651|288.0 |
|twins_svt_base.in1k                                   |12.119240760803223|87.651|224.0 |
|mobilevitv2_150.cvnets_in22k_ft_in1k_384              |16.138205528259277|87.649|384.0 |
|coat_small.in1k                                       |21.041269302368164|87.647|224.0 |
|maxxvitv2_nano_rw_256.sw_in1k                         |50.343003273010254|87.638|256.0 |
|pnasnet5large.tf_in1k                                 |37.444305419921875|87.636|331.0 |
|resnet101.a1h_in1k                                    |11.153712272644043|87.634|288.0 |
|resnetaa50d.sw_in12k_ft_in1k                          |7.480440139770508 |87.623|288.0 |
|flexivit_small.300ep_in1k                             |5.266742706298828 |87.623|240.0 |
|cs3edgenet_x.c2_in1k                                  |8.217339515686035 |87.621|288.0 |
|xcit_medium_24_p8_224.fb_in1k                         |43.30172061920166 |87.612|224.0 |
|swinv2_tiny_window16_256.ms_in1k                      |10.904059410095215|87.61 |256.0 |
|resnext101_32x16d.fb_swsl_ig1b_ft_in1k                |30.79679012298584 |87.606|224.0 |
|resnext50_32x4d.fb_swsl_ig1b_ft_in1k                  |6.919994354248047 |87.6  |224.0 |
|nest_base_jx.goog_in1k                                |13.098669052124023|87.597|224.0 |
|maxvit_nano_rw_256.sw_in1k                            |11.4076566696167  |87.595|256.0 |
|tf_efficientnet_b4.in1k                               |16.02635383605957 |87.582|380.0 |
|davit_tiny.msft_in1k                                  |7.726240158081055 |87.565|224.0 |
|levit_384.fb_dist_in1k                                |7.935194969177246 |87.563|224.0 |
|levit_conv_384.fb_dist_in1k                           |8.022308349609375 |87.561|224.0 |
|sequencer2d_m.in1k                                    |25.60194969177246 |87.559|224.0 |
|convnextv2_nano.fcmae_ft_in1k                         |8.82075309753418  |87.553|288.0 |
|tf_efficientnet_b2.ns_jft_in1k                        |10.176668167114258|87.553|260.0 |
|ecaresnet50t.ra2_in1k                                 |9.422602653503418 |87.544|320.0 |
|regnetx_320.tv2_in1k                                  |21.803975105285645|87.538|224.0 |
|vit_base_patch32_clip_224.laion2b_ft_in1k             |5.151991844177246 |87.529|224.0 |
|efficientformerv2_s2.snap_dist_in1k                   |14.975438117980957|87.514|224.0 |
|coatnet_bn_0_rw_224.sw_in1k                           |8.225326538085938 |87.508|224.0 |
|vit_base_patch16_rpn_224.sw_in1k                      |7.112536430358887 |87.504|224.0 |
|pvt_v2_b2_li.in1k                                     |10.604753494262695|87.501|224.0 |
|resnetv2_152x2_bit.goog_teacher_in21k_ft_in1k         |35.77436447143555 |87.497|224.0 |
|edgenext_small.usi_in1k                               |49.731082916259766|87.493|320.0 |
|nest_small_jx.goog_in1k                               |10.047135353088379|87.493|224.0 |
|vit_relpos_base_patch16_clsgap_224.sw_in1k            |7.982935905456543 |87.471|224.0 |
|vit_relpos_base_patch16_224.sw_in1k                   |8.097124099731445 |87.467|224.0 |
|regnety_080_tv.tv2_in1k                               |12.090263366699219|87.465|224.0 |
|fbnetv3_g.ra2_in1k                                    |12.890658378601074|87.446|288.0 |
|resnet61q.ra2_in1k                                    |12.197990417480469|87.439|288.0 |
|wide_resnet50_2.racm_in1k                             |10.789270401000977|87.437|288.0 |
|poolformerv2_m48.sail_in1k                            |24.66928005218506 |87.435|224.0 |
|efficientnet_b3.ra2_in1k                              |11.433725357055664|87.433|320.0 |
|regnetx_160.tv2_in1k                                  |13.619952201843262|87.433|224.0 |
|resnext101_64x4d.c1_in1k                              |25.221705436706543|87.433|288.0 |
|cait_xxs24_384.fb_dist_in1k                           |33.04924011230469 |87.414|384.0 |
|resnet51q.ra2_in1k                                    |10.09882926940918 |87.397|288.0 |
|cs3darknet_x.c2ns_in1k                                |8.25387954711914  |87.395|288.0 |
|cs3sedarknet_l.c2ns_in1k                              |9.63268756866455  |87.395|288.0 |
|coat_lite_small.in1k                                  |12.45203971862793 |87.388|224.0 |
|tresnet_l.miil_in1k_448                               |25.263447761535645|87.382|448.0 |
|resnetv2_50d_gn.ah_in1k                               |7.828502655029297 |87.38 |288.0 |
|pvt_v2_b2.in1k                                        |9.67041015625     |87.377|224.0 |
|sequencer2d_s.in1k                                    |20.152859687805176|87.377|224.0 |
|swinv2_cr_small_224.sw_in1k                           |15.472898483276367|87.377|224.0 |
|xcit_tiny_24_p8_224.fb_in1k                           |17.57697582244873 |87.373|224.0 |
|vit_relpos_medium_patch16_cls_224.sw_in1k             |7.220416069030762 |87.363|224.0 |
|nasnetalarge.tf_in1k                                  |37.35158443450928 |87.36 |331.0 |
|crossvit_18_dagger_240.in1k                           |11.86530590057373 |87.352|240.0 |
|seresnext50_32x4d.racm_in1k                           |11.02193832397461 |87.35 |288.0 |
|wide_resnet101_2.tv2_in1k                             |12.848782539367676|87.326|224.0 |
|ecaresnet50d.miil_in1k                                |8.323974609375    |87.322|288.0 |
|resnext101_32x8d.tv2_in1k                             |17.494525909423828|87.318|224.0 |
|crossvit_18_240.in1k                                  |11.46106243133545 |87.316|240.0 |
|focalnet_tiny_srf.ms_in1k                             |9.164133071899414 |87.301|224.0 |
|resnest101e.in1k                                      |19.81907367706299 |87.29 |256.0 |
|gcvit_xtiny.in1k                                      |16.17082118988037 |87.281|224.0 |
|coatnet_rmlp_nano_rw_224.sw_in1k                      |10.381903648376465|87.277|224.0 |
|ecaresnet101d_pruned.miil_in1k                        |14.765639305114746|87.273|288.0 |
|vit_relpos_medium_patch16_rpn_224.sw_in1k             |6.860942840576172 |87.269|224.0 |
|swin_tiny_patch4_window7_224.ms_in22k_ft_in1k         |6.749711036682129 |87.249|224.0 |
|resnetrs101.tf_in1k                                   |17.13418960571289 |87.241|288.0 |
|coatnext_nano_rw_224.sw_in1k                          |10.721850395202637|87.239|224.0 |
|poolformer_m48.sail_in1k                              |21.231727600097656|87.237|224.0 |
|regnety_160.tv2_in1k                                  |15.390486717224121|87.234|224.0 |
|tresnet_xl.miil_in1k                                  |17.70198345184326 |87.232|224.0 |
|mixer_b16_224.miil_in21k_ft_in1k                      |5.324468612670898 |87.23 |224.0 |
|xcit_tiny_12_p8_224.fb_dist_in1k                      |9.955430030822754 |87.224|224.0 |
|xcit_tiny_12_p16_384.fb_dist_in1k                     |11.588201522827148|87.209|384.0 |
|convit_base.fb_in1k                                   |10.60793399810791 |87.209|224.0 |
|resnetv2_50d_evos.ah_in1k                             |13.187317848205566|87.205|288.0 |
|tf_efficientnet_b3.ap_in1k                            |11.840729713439941|87.19 |300.0 |
|resnet152.tv2_in1k                                    |15.75629711151123 |87.188|224.0 |
|visformer_small.in1k                                  |7.327413558959961 |87.183|224.0 |
|vit_base_patch32_clip_224.openai_ft_in1k              |5.166769027709961 |87.179|224.0 |
|vit_srelpos_medium_patch16_224.sw_in1k                |5.6117963790893555|87.177|224.0 |
|focalnet_tiny_lrf.ms_in1k                             |9.674038887023926 |87.175|224.0 |
|crossvit_15_dagger_240.in1k                           |10.671224594116211|87.164|240.0 |
|convnext_tiny_hnf.a2h_in1k                            |9.95297908782959  |87.147|288.0 |
|vit_relpos_medium_patch16_224.sw_in1k                 |7.366385459899902 |87.145|224.0 |
|swin_s3_tiny_224.ms_in1k                              |6.614251136779785 |87.143|224.0 |
|coatnet_0_rw_224.sw_in1k                              |9.017777442932129 |87.128|224.0 |
|xcit_small_24_p16_224.fb_in1k                         |17.821006774902344|87.119|224.0 |
|swinv2_tiny_window8_256.ms_in1k                       |9.175896644592285 |87.089|256.0 |
|pit_s_distilled_224.in1k                              |29.139928817749023|87.081|224.0 |
|ecaresnet50t.a1_in1k                                  |8.029942512512207 |87.081|288.0 |
|xception41p.ra3_in1k                                  |9.323678016662598 |87.059|299.0 |
|mobilevitv2_200.cvnets_in22k_ft_in1k                  |10.171852111816406|87.057|256.0 |
|resnext50_32x4d.a1h_in1k                              |9.472956657409668 |87.057|288.0 |
|regnetz_b16.ra3_in1k                                  |13.51306438446045 |87.047|288.0 |
|crossvit_15_240.in1k                                  |10.129694938659668|87.044|240.0 |
|convit_small.fb_in1k                                  |6.7118120193481445|87.042|224.0 |
|gcresnet50t.ra2_in1k                                  |11.41594409942627 |87.029|288.0 |
|tf_efficientnetv2_b3.in1k                             |12.538681030273438|87.027|300.0 |
|xcit_small_12_p16_224.fb_in1k                         |10.683832168579102|87.012|224.0 |
|poolformerv2_m36.sail_in1k                            |18.834104537963867|87.008|224.0 |
|nest_tiny_jx.goog_in1k                                |6.653304100036621 |87.006|224.0 |
|deit_small_distilled_patch16_224.fb_in1k              |5.511326789855957 |87.006|224.0 |
|deit3_small_patch16_224.fb_in1k                       |5.41234016418457  |87.006|224.0 |
|swinv2_cr_tiny_ns_224.sw_in1k                         |8.478164672851562 |87.002|224.0 |
|resnet101.a1_in1k                                     |11.585297584533691|87.0  |288.0 |
|coatnet_nano_rw_224.sw_in1k                           |9.422893524169922 |86.995|224.0 |
|resnet152.a2_in1k                                     |16.148815155029297|86.995|288.0 |
|resmlp_36_224.fb_distilled_in1k                       |7.595181465148926 |86.987|224.0 |
|poolformer_m36.sail_in1k                              |16.089258193969727|86.955|224.0 |
|mobilevitv2_175.cvnets_in22k_ft_in1k                  |8.961882591247559 |86.951|256.0 |
|resnet101.a2_in1k                                     |11.555895805358887|86.942|288.0 |
|regnety_032.tv2_in1k                                  |12.03866958618164 |86.94 |224.0 |
|xcit_large_24_p16_224.fb_in1k                         |18.76796245574951 |86.94 |224.0 |
|resnet101.tv2_in1k                                    |10.552921295166016|86.936|224.0 |
|xcit_medium_24_p16_224.fb_in1k                        |17.989625930786133|86.933|224.0 |
|resnetv2_50.a1h_in1k                                  |7.058014869689941 |86.929|288.0 |
|poolformerv2_s36.sail_in1k                            |13.107023239135742|86.923|224.0 |
|tnt_s_patch16_224                                     |11.955389976501465|86.914|224.0 |
|vit_relpos_small_patch16_224.sw_in1k                  |7.290520668029785 |86.891|224.0 |
|vit_small_patch16_224.augreg_in21k_ft_in1k            |5.186629295349121 |86.867|224.0 |
|vit_small_r26_s32_224.augreg_in21k_ft_in1k            |9.78489875793457  |86.863|224.0 |
|resnet152.a1_in1k                                     |16.061339378356934|86.861|288.0 |
|ecaresnetlight.miil_in1k                              |8.116531372070312 |86.852|288.0 |
|resnext101_32x16d.fb_ssl_yfcc100m_ft_in1k             |30.716042518615723|86.846|224.0 |
|tf_efficientnet_b3.aa_in1k                            |11.797690391540527|86.844|300.0 |
|rexnet_200.nav_in1k                                   |7.901062965393066 |86.842|224.0 |
|convmixer_1536_20.in1k                                |41.081480979919434|86.84 |224.0 |
|resnet50.fb_swsl_ig1b_ft_in1k                         |6.172785758972168 |86.831|224.0 |
|deit_base_patch16_224.fb_in1k                         |7.182879447937012 |86.829|224.0 |
|tresnet_m.miil_in1k_448                               |14.157085418701172|86.816|448.0 |
|tf_efficientnet_lite4.in1k                            |12.099103927612305|86.801|380.0 |
|coat_mini.in1k                                        |93.53187084197998 |86.799|224.0 |
|resnext101_32x8d.fb_ssl_yfcc100m_ft_in1k              |17.49588966369629 |86.795|224.0 |
|eva02_tiny_patch14_336.mim_in22k_ft_in1k              |8.201518058776855 |86.786|336.0 |
|seresnet50.ra2_in1k                                   |8.873634338378906 |86.778|288.0 |
|vit_base_patch16_224.orig_in21k_ft_in1k               |7.180604934692383 |86.773|224.0 |
|convnextv2_pico.fcmae_ft_in1k                         |6.746349334716797 |86.773|288.0 |
|regnetx_080.tv2_in1k                                  |9.248270988464355 |86.771|224.0 |
|cs3darknet_l.c2ns_in1k                                |7.21832275390625  |86.767|288.0 |
|resnetaa50.a1h_in1k                                   |7.239184379577637 |86.763|288.0 |
|tresnet_l.miil_in1k                                   |14.286818504333496|86.763|224.0 |
|resnet50d.ra2_in1k                                    |7.284674644470215 |86.76 |288.0 |
|ese_vovnet39b.ra_in1k                                 |6.950259208679199 |86.756|288.0 |
|resnet50_gn.a1h_in1k                                  |7.5850677490234375|86.754|288.0 |
|twins_svt_small.in1k                                  |9.646072387695312 |86.754|224.0 |
|seresnet50.a1_in1k                                    |8.947358131408691 |86.746|288.0 |
|mobilevitv2_150.cvnets_in22k_ft_in1k                  |7.563109397888184 |86.743|256.0 |
|crossvit_base_240.in1k                                |10.61683177947998 |86.733|240.0 |
|levit_256.fb_dist_in1k                                |7.925205230712891 |86.731|224.0 |
|levit_conv_256.fb_dist_in1k                           |7.620687484741211 |86.726|224.0 |
|ecaresnet50t.a2_in1k                                  |8.431363105773926 |86.726|288.0 |
|cs3darknet_focus_l.c2ns_in1k                          |7.209453582763672 |86.724|288.0 |
|convnext_nano_ols.d1h_in1k                            |7.461352348327637 |86.718|288.0 |
|vit_srelpos_small_patch16_224.sw_in1k                 |5.865778923034668 |86.707|224.0 |
|resnet50.ram_in1k                                     |6.890263557434082 |86.699|288.0 |
|halo2botnet50ts_256.a1h_in1k                          |10.234780311584473|86.688|256.0 |
|pit_b_224.in1k                                        |53.50013256072998 |86.688|224.0 |
|crossvit_small_240.in1k                               |9.133625030517578 |86.686|240.0 |
|resnet50d.a1_in1k                                     |7.332124710083008 |86.671|288.0 |
|ecaresnet50d_pruned.miil_in1k                         |7.862753868103027 |86.669|288.0 |
|tf_efficientnet_b1.ns_jft_in1k                        |9.593634605407715 |86.669|240.0 |
|swin_tiny_patch4_window7_224.ms_in1k                  |6.851544380187988 |86.658|224.0 |
|poolformer_s36.sail_in1k                              |11.999826431274414|86.654|224.0 |
|gernet_l.idstcv_in1k                                  |6.534523963928223 |86.643|256.0 |
|efficientnet_el.ra_in1k                               |9.165830612182617 |86.63 |300.0 |
|twins_pcpvt_small.in1k                                |9.169292449951172 |86.62 |224.0 |
|resmlp_24_224.fb_distilled_in1k                       |5.61737060546875  |86.615|224.0 |
|gcresnext50ts.ch_in1k                                 |13.409876823425293|86.609|288.0 |
|resnet50.c2_in1k                                      |6.810564994812012 |86.605|288.0 |
|nf_resnet50.ra2_in1k                                  |9.204668998718262 |86.592|288.0 |
|resnest50d_4s2x40d.in1k                               |10.954833030700684|86.588|224.0 |
|sebotnet33ts_256.a1h_in1k                             |7.644872665405273 |86.585|256.0 |
|repvgg_b3.rvgg_in1k                                   |12.153768539428711|86.579|224.0 |
|efficientnet_b3_pruned.in1k                           |10.88465690612793 |86.577|300.0 |
|wide_resnet50_2.tv2_in1k                              |7.576560974121094 |86.57 |224.0 |
|sehalonet33ts.ra2_in1k                                |7.916326522827148 |86.566|256.0 |
|resnet50.a1_in1k                                      |6.9905900955200195|86.541|288.0 |
|resnet50.c1_in1k                                      |7.148241996765137 |86.536|288.0 |
|convnext_nano.d1h_in1k                                |7.073912620544434 |86.536|288.0 |
|xcit_tiny_24_p16_224.fb_dist_in1k                     |18.29763412475586 |86.534|224.0 |
|seresnet50.a2_in1k                                    |8.955821990966797 |86.519|288.0 |
|vit_small_patch16_384.augreg_in1k                     |11.158170700073242|86.502|384.0 |
|halonet50ts.a1h_in1k                                  |9.632902145385742 |86.487|256.0 |
|resnext101_32x4d.fb_ssl_yfcc100m_ft_in1k              |12.848310470581055|86.485|224.0 |
|maxvit_rmlp_pico_rw_256.sw_in1k                       |18.46445083618164 |86.481|256.0 |
|resnet152s.gluon_in1k                                 |15.810151100158691|86.466|224.0 |
|haloregnetz_b.ra3_in1k                                |13.149833679199219|86.466|224.0 |
|mobilevitv2_200.cvnets_in1k                           |10.18075942993164 |86.457|256.0 |
|seresnet33ts.ra2_in1k                                 |6.813864707946777 |86.455|288.0 |
|resnext50d_32x4d.bt_in1k                              |9.813799858093262 |86.455|288.0 |
|resnet50.d_in1k                                       |6.814398765563965 |86.455|288.0 |
|resnet50.tv2_in1k                                     |5.9709978103637695|86.442|224.0 |
|resnetv2_50x1_bit.goog_in21k_ft_in1k                  |16.631169319152832|86.44 |448.0 |
|resnet50.b1k_in1k                                     |6.926813125610352 |86.44 |288.0 |
|resnest50d_1s4x24d.in1k                               |9.72628116607666  |86.432|224.0 |
|poolformerv2_s24.sail_in1k                            |9.402523040771484 |86.389|224.0 |
|repvgg_b3g4.rvgg_in1k                                 |10.403642654418945|86.368|224.0 |
|regnety_016.tv2_in1k                                  |18.151988983154297|86.365|224.0 |
|darknetaa53.c2ns_in1k                                 |6.934418678283691 |86.361|288.0 |
|efficientformer_l1.snap_dist_in1k                     |5.736727714538574 |86.357|224.0 |
|darknet53.c2ns_in1k                                   |7.081875801086426 |86.353|288.0 |
|lamhalobotnet50ts_256.a1h_in1k                        |9.71489429473877  |86.353|256.0 |
|legacy_senet154.in1k                                  |30.55281639099121 |86.344|224.0 |
|resnet50.a1h_in1k                                     |6.215949058532715 |86.34 |224.0 |
|cait_xxs36_224.fb_dist_in1k                           |18.938794136047363|86.329|224.0 |
|tf_efficientnet_b3.in1k                               |11.221098899841309|86.323|300.0 |
|gernet_m.idstcv_in1k                                  |5.168027877807617 |86.321|224.0 |
|mobilevitv2_175.cvnets_in1k                           |8.820991516113281 |86.321|256.0 |
|resnet50d.a2_in1k                                     |7.304339408874512 |86.314|288.0 |
|vit_small_patch32_384.augreg_in21k_ft_in1k            |6.284003257751465 |86.31 |384.0 |
|efficientnet_b2.ra_in1k                               |9.998817443847656 |86.31 |288.0 |
|gcresnet33ts.ra2_in1k                                 |8.153033256530762 |86.304|288.0 |
|pit_s_224.in1k                                        |29.16767120361328 |86.304|224.0 |
|resnext50_32x4d.a1_in1k                               |9.406166076660156 |86.284|288.0 |
|resnext50_32x4d.a2_in1k                               |9.448676109313965 |86.28 |288.0 |
|resnet50.b2k_in1k                                     |7.010898590087891 |86.272|288.0 |
|senet154.gluon_in1k                                   |31.174516677856445|86.272|224.0 |
|resnext50_32x4d.tv2_in1k                              |7.03709602355957  |86.269|224.0 |
|eca_resnet33ts.ra2_in1k                               |6.2874650955200195|86.257|288.0 |
|resnest50d.in1k                                       |10.30754566192627 |86.248|224.0 |
|gcvit_xxtiny.in1k                                     |14.35384750366211 |86.244|224.0 |
|regnetx_032.tv2_in1k                                  |10.179872512817383|86.244|224.0 |
|vit_base_patch16_384.augreg_in1k                      |24.611034393310547|86.229|384.0 |
|convmixer_768_32.in1k                                 |23.767099380493164|86.22 |224.0 |
|cspdarknet53.ra_in1k                                  |8.092918395996094 |86.19 |256.0 |
|efficientnet_el_pruned.in1k                           |9.048528671264648 |86.186|300.0 |
|tresnet_m.miil_in1k                                   |10.544047355651855|86.186|224.0 |
|rexnet_150.nav_in1k                                   |8.139362335205078 |86.171|224.0 |
|inception_v4.tf_in1k                                  |16.313648223876953|86.163|299.0 |
|inception_resnet_v2.tf_in1k                           |26.617450714111328|86.131|299.0 |
|xcit_tiny_12_p8_224.fb_in1k                           |9.765148162841797 |86.114|224.0 |
|resnext50_32x4d.fb_ssl_yfcc100m_ft_in1k               |6.962404251098633 |86.101|224.0 |
|res2net101d.in1k                                      |18.592019081115723|86.099|224.0 |
|resnet50.a2_in1k                                      |7.411537170410156 |86.097|288.0 |
|tf_efficientnet_el.in1k                               |9.354162216186523 |86.082|300.0 |
|mobilevitv2_150.cvnets_in1k                           |7.962350845336914 |86.082|256.0 |
|cspresnext50.ra_in1k                                  |7.9900407791137695|86.077|256.0 |
|convnext_pico_ols.d1_in1k                             |5.466499328613281 |86.067|288.0 |
|resnet101s.gluon_in1k                                 |11.091961860656738|86.064|224.0 |
|edgenext_small_rw.sw_in1k                             |57.77717113494873 |86.054|320.0 |
|lambda_resnet50ts.a1h_in1k                            |8.79343032836914  |86.047|256.0 |
|seresnext101_32x4d.gluon_in1k                         |18.07985782623291 |86.026|224.0 |
|poolformer_s24.sail_in1k                              |8.62302303314209  |86.013|224.0 |
|convnext_pico.d1_in1k                                 |5.363655090332031 |86.013|288.0 |
|resnetblur50.bt_in1k                                  |7.344307899475098 |85.996|288.0 |
|tf_efficientnet_b2.ap_in1k                            |10.332427024841309|85.981|260.0 |
|ecaresnet26t.ra2_in1k                                 |6.195263862609863 |85.979|320.0 |
|resnet152.a3_in1k                                     |15.555005073547363|85.979|224.0 |
|seresnext101_64x4d.gluon_in1k                         |20.503239631652832|85.973|224.0 |
|efficientformerv2_s1.snap_dist_in1k                   |10.668044090270996|85.962|224.0 |
|vit_base_patch32_224.augreg_in21k_ft_in1k             |5.129580497741699 |85.956|224.0 |
|resnext50_32x4d.ra_in1k                               |9.378914833068848 |85.932|288.0 |
|fbnetv3_d.ra2_in1k                                    |11.282272338867188|85.93 |256.0 |
|resnet152d.gluon_in1k                                 |15.514497756958008|85.919|224.0 |
|vit_large_patch32_384.orig_in21k_ft_in1k              |17.000904083251953|85.911|384.0 |
|tf_efficientnet_b2.aa_in1k                            |10.379815101623535|85.896|260.0 |
|tf_efficientnetv2_b2.in1k                             |10.987629890441895|85.885|260.0 |
|vit_base_patch16_224.sam_in1k                         |7.155356407165527 |85.872|224.0 |
|resnet101d.gluon_in1k                                 |11.533036231994629|85.864|224.0 |
|repvgg_b2g4.rvgg_in1k                                 |8.389244079589844 |85.862|224.0 |
|mixnet_xl.ra_in1k                                     |14.000444412231445|85.804|224.0 |
|inception_resnet_v2.tf_ens_adv_in1k                   |26.157150268554688|85.763|299.0 |
|tf_efficientnet_lite3.in1k                            |7.04803466796875  |85.757|300.0 |
|resnext101_32x4d.gluon_in1k                           |12.887883186340332|85.753|224.0 |
|xcit_tiny_24_p16_224.fb_in1k                          |18.33548069000244 |85.746|224.0 |
|legacy_seresnext101_32x4d.in1k                        |17.621021270751953|85.742|224.0 |
|resnet101.a3_in1k                                     |10.528268814086914|85.74 |224.0 |
|res2net50d.in1k                                       |9.996471405029297 |85.729|224.0 |
|regnety_320.pycls_in1k                                |19.834675788879395|85.729|224.0 |
|cspresnet50.ra_in1k                                   |7.315421104431152 |85.725|256.0 |
|resmlp_big_24_224.fb_in1k                             |33.879990577697754|85.701|224.0 |
|resnext101_64x4d.gluon_in1k                           |17.691540718078613|85.693|224.0 |
|resnet33ts.ra2_in1k                                   |5.918922424316406 |85.691|288.0 |
|xception71.tf_in1k                                    |17.764859199523926|85.689|299.0 |
|resnet50.ra_in1k                                      |6.932168006896973 |85.674|288.0 |
|ecaresnet50t.a3_in1k                                  |7.934737205505371 |85.674|224.0 |
|deit_small_patch16_224.fb_in1k                        |5.171232223510742 |85.672|224.0 |
|dpn107.mx_in1k                                        |22.509078979492188|85.672|224.0 |
|efficientnet_em.ra2_in1k                              |6.386704444885254 |85.667|240.0 |
|efficientnet_b2_pruned.in1k                           |10.233354568481445|85.644|260.0 |
|resmlp_36_224.fb_in1k                                 |7.70573616027832  |85.623|224.0 |
|mobilevitv2_125.cvnets_in1k                           |7.968258857727051 |85.578|256.0 |
|resnet50.bt_in1k                                      |7.0555830001831055|85.576|288.0 |
|levit_conv_192.fb_dist_in1k                           |7.4245405197143555|85.571|224.0 |
|resnet32ts.ra2_in1k                                   |5.9210205078125   |85.569|288.0 |
|levit_192.fb_dist_in1k                                |7.963895797729492 |85.569|224.0 |
|resnet152c.gluon_in1k                                 |15.635600090026855|85.567|224.0 |
|pit_xs_distilled_224.in1k                             |20.203700065612793|85.565|224.0 |
|tf_efficientnetv2_b1.in1k                             |9.813146591186523 |85.556|240.0 |
|regnety_120.pycls_in1k                                |12.863807678222656|85.55 |224.0 |
|fbnetv3_b.ra2_in1k                                    |10.174264907836914|85.52 |256.0 |
|regnetx_320.pycls_in1k                                |21.806111335754395|85.52 |224.0 |
|convnextv2_femto.fcmae_ft_in1k                        |6.026954650878906 |85.503|288.0 |
|nf_regnet_b1.ra2_in1k                                 |13.708395957946777|85.503|288.0 |
|dpn92.mx_in1k                                         |13.30927848815918 |85.503|224.0 |
|regnety_160.pycls_in1k                                |15.418715476989746|85.49 |224.0 |
|resnet152.gluon_in1k                                  |15.402426719665527|85.479|224.0 |
|resnetrs50.tf_in1k                                    |8.63579273223877  |85.475|224.0 |
|rexnet_130.nav_in1k                                   |8.05598258972168  |85.469|224.0 |
|dpn131.mx_in1k                                        |21.285419464111328|85.45 |224.0 |
|regnetx_160.pycls_in1k                                |13.609585762023926|85.396|224.0 |
|tf_efficientnet_b2.in1k                               |10.560340881347656|85.396|260.0 |
|convnext_tiny.fb_in22k_ft_in1k                        |7.453093528747559 |85.381|288.0 |
|dla102x2.in1k                                         |15.80132007598877 |85.375|224.0 |
|dpn98.mx_in1k                                         |15.736532211303711|85.351|224.0 |
|regnetx_016.tv2_in1k                                  |6.960501670837402 |85.349|224.0 |
|gmlp_s16_224.ra3_in1k                                 |7.30015754699707  |85.349|224.0 |
|botnet26t_256.c1_in1k                                 |5.887460708618164 |85.332|256.0 |
|seresnext50_32x4d.gluon_in1k                          |9.51871395111084  |85.328|224.0 |
|skresnext50_32x4d.ra_in1k                             |13.299574851989746|85.328|224.0 |
|xception65.tf_in1k                                    |13.991894721984863|85.315|299.0 |
|resnet101c.gluon_in1k                                 |11.098051071166992|85.306|224.0 |
|lambda_resnet26t.c1_in1k                              |5.395646095275879 |85.298|256.0 |
|resnext50_32x4d.a3_in1k                               |6.897153854370117 |85.298|224.0 |
|regnety_064.pycls_in1k                                |14.905033111572266|85.283|224.0 |
|resnet34d.ra2_in1k                                    |5.4586076736450195|85.272|288.0 |
|coat_lite_mini.in1k                                   |7.224826812744141 |85.272|224.0 |
|resmlp_24_224.fb_in1k                                 |5.390510559082031 |85.264|224.0 |
|convnext_femto_ols.d1_in1k                            |4.667873382568359 |85.253|288.0 |
|cait_xxs24_224.fb_dist_in1k                           |13.64572525024414 |85.238|224.0 |
|regnety_080.pycls_in1k                                |12.146244049072266|85.238|224.0 |
|pvt_v2_b1.in1k                                        |5.700287818908691 |85.21 |224.0 |
|xcit_tiny_12_p16_224.fb_dist_in1k                     |10.422658920288086|85.2  |224.0 |
|halonet26t.a1h_in1k                                   |5.543127059936523 |85.193|256.0 |
|inception_v3.gluon_in1k                               |10.39644718170166 |85.189|299.0 |
|resnext101_32x8d.tv_in1k                              |17.467308044433594|85.189|224.0 |
|convnext_femto.d1_in1k                                |4.872074127197266 |85.163|288.0 |
|resnet101.gluon_in1k                                  |10.770421028137207|85.163|224.0 |
|hrnet_w48.ms_in1k                                     |31.484904289245605|85.155|224.0 |
|regnetx_120.pycls_in1k                                |11.235747337341309|85.138|224.0 |
|eca_halonext26ts.c1_in1k                              |5.923013687133789 |85.131|256.0 |
|resnet50.am_in1k                                      |6.094346046447754 |85.131|224.0 |
|tf_efficientnet_b1.ap_in1k                            |9.631643295288086 |85.131|240.0 |
|eca_botnext26ts_256.c1_in1k                           |6.246895790100098 |85.121|256.0 |
|legacy_xception.tf_in1k                               |8.411836624145508 |85.121|299.0 |
|hrnet_w64.ms_in1k                                     |32.94421195983887 |85.112|224.0 |
|resnet50.fb_ssl_yfcc100m_ft_in1k                      |5.921664237976074 |85.102|224.0 |
|lambda_resnet26rpt_256.c1_in1k                        |5.661840438842773 |85.099|256.0 |
|res2net101_26w_4s.in1k                                |18.41902256011963 |85.097|224.0 |
|tf_efficientnet_cc_b1_8e.in1k                         |12.034635543823242|85.065|240.0 |
|dpn68b.ra_in1k                                        |12.000675201416016|85.061|288.0 |
|resnest26d.gluon_in1k                                 |6.106300354003906 |85.016|224.0 |
|xcit_nano_12_p8_384.fb_dist_in1k                      |17.018632888793945|85.014|384.0 |
|resnext50_32x4d.gluon_in1k                            |6.74224853515625  |85.005|224.0 |
|tf_efficientnet_b0.ns_jft_in1k                        |7.066245079040527 |84.999|224.0 |
|coat_tiny.in1k                                        |68.86227130889893 |84.971|224.0 |
|regnety_040.pycls_in1k                                |13.15772533416748 |84.956|224.0 |
|dla169.in1k                                           |16.574277877807617|84.929|224.0 |
|tf_efficientnet_b1.aa_in1k                            |9.566082954406738 |84.918|240.0 |
|resnet50d.a3_in1k                                     |6.204981803894043 |84.903|224.0 |
|legacy_seresnext50_32x4d.in1k                         |9.38197135925293  |84.897|224.0 |
|mobilevitv2_100.cvnets_in1k                           |7.078795433044434 |84.894|256.0 |
|hrnet_w44.ms_in1k                                     |31.754908561706543|84.884|224.0 |
|regnety_008_tv.tv2_in1k                               |8.192586898803711 |84.879|224.0 |
|resnet50s.gluon_in1k                                  |6.20424747467041  |84.879|224.0 |
|regnetx_080.pycls_in1k                                |9.204692840576172 |84.865|224.0 |
|visformer_tiny.in1k                                   |6.490011215209961 |84.847|224.0 |
|levit_conv_128.fb_dist_in1k                           |7.228550910949707 |84.847|224.0 |
|levit_128.fb_dist_in1k                                |8.119235038757324 |84.845|224.0 |
|resnet50d.gluon_in1k                                  |6.387152671813965 |84.837|224.0 |
|res2net50_26w_8s.in1k                                 |16.25821590423584 |84.837|224.0 |
|dla60_res2next.in1k                                   |11.43381118774414 |84.83 |224.0 |
|vit_tiny_patch16_384.augreg_in21k_ft_in1k             |7.218289375305176 |84.824|384.0 |
|resnet152.tv_in1k                                     |15.966596603393555|84.824|224.0 |
|dla60_res2net.in1k                                    |11.256575584411621|84.822|224.0 |
|resnet26t.ra2_in1k                                    |5.819482803344727 |84.822|320.0 |
|mixnet_l.ft_in1k                                      |11.235489845275879|84.818|224.0 |
|dla102x.in1k                                          |13.114867210388184|84.807|224.0 |
|hrnet_w18.ms_aug_in1k                                 |29.748806953430176|84.785|224.0 |
|xception41.tf_in1k                                    |10.32844066619873 |84.785|299.0 |
|pit_xs_224.in1k                                       |20.13861656188965 |84.781|224.0 |
|regnetx_064.pycls_in1k                                |8.788518905639648 |84.771|224.0 |
|resnet34.a1_in1k                                      |4.959731101989746 |84.762|288.0 |
|poolformerv2_s12.sail_in1k                            |5.319223403930664 |84.756|224.0 |
|gcresnext26ts.ch_in1k                                 |7.316312789916992 |84.756|288.0 |
|hrnet_w40.ms_in1k                                     |31.522841453552246|84.745|224.0 |
|repvgg_b2.rvgg_in1k                                   |8.877644538879395 |84.726|224.0 |
|res2net50_26w_6s.in1k                                 |13.182549476623535|84.726|224.0 |
|resmlp_12_224.fb_distilled_in1k                       |3.3080339431762695|84.719|224.0 |
|vit_base_patch32_384.augreg_in1k                      |7.610883712768555 |84.717|384.0 |
|legacy_seresnet152.in1k                               |22.812294960021973|84.709|224.0 |
|cs3darknet_m.c2ns_in1k                                |5.822906494140625 |84.694|288.0 |
|SelecSls60b.in1k                                      |6.596388816833496 |84.662|224.0 |
|bat_resnext26ts.ch_in1k                               |11.523194313049316|84.653|256.0 |
|hrnet_w32.ms_in1k                                     |30.94170570373535 |84.649|224.0 |
|seresnext26d_32x4d.bt_in1k                            |7.133941650390625 |84.642|288.0 |
|tf_efficientnetv2_b0.in1k                             |8.22995662689209  |84.625|224.0 |
|efficientnet_b1.ft_in1k                               |9.613180160522461 |84.611|256.0 |
|regnetx_040.pycls_in1k                                |10.876274108886719|84.604|224.0 |
|regnety_032.pycls_in1k                                |12.386131286621094|84.6  |224.0 |
|vit_relpos_base_patch32_plus_rpn_256.sw_in1k          |7.367000579833984 |84.598|256.0 |
|seresnext26t_32x4d.bt_in1k                            |7.26503849029541  |84.589|288.0 |
|hrnet_w30.ms_in1k                                     |31.90868377685547 |84.583|224.0 |
|efficientnet_es.ra_in1k                               |4.902791976928711 |84.583|224.0 |
|tf_mixnet_l.in1k                                      |11.857070922851562|84.572|224.0 |
|wide_resnet101_2.tv_in1k                              |12.818279266357422|84.549|224.0 |
|vit_small_patch16_224.augreg_in1k                     |5.244426727294922 |84.531|224.0 |
|dla60x.in1k                                           |7.98123836517334  |84.529|224.0 |
|legacy_seresnet101.in1k                               |15.64168930053711 |84.499|224.0 |
|cs3darknet_focus_m.c2ns_in1k                          |5.651121139526367 |84.482|288.0 |
|seresnext26ts.ch_in1k                                 |6.323995590209961 |84.482|288.0 |
|resnet50.a3_in1k                                      |6.09285831451416  |84.482|224.0 |
|tf_efficientnet_b1.in1k                               |9.84611988067627  |84.478|240.0 |
|coat_lite_tiny.in1k                                   |12.799439430236816|84.459|224.0 |
|tf_efficientnet_em.in1k                               |6.465177536010742 |84.453|240.0 |
|wide_resnet50_2.tv_in1k                               |7.414522171020508 |84.429|224.0 |
|repvgg_b1.rvgg_in1k                                   |7.861309051513672 |84.42 |224.0 |
|efficientnet_b1_pruned.in1k                           |9.617786407470703 |84.391|240.0 |
|vit_base_patch16_224.augreg_in1k                      |7.182884216308594 |84.388|224.0 |
|res2net50_26w_4s.in1k                                 |10.06901741027832 |84.359|224.0 |
|hardcorenas_f.miil_green_in1k                         |7.1459197998046875|84.32 |224.0 |
|res2net50_14w_8s.in1k                                 |15.38550853729248 |84.311|224.0 |
|SelecSls60.in1k                                       |6.522130966186523 |84.284|224.0 |
|mobilevit_s.cvnets_in1k                               |8.228974342346191 |84.275|256.0 |
|regnetx_032.pycls_in1k                                |10.079340934753418|84.245|224.0 |
|ese_vovnet19b_dw.ra_in1k                              |4.6211957931518555|84.226|288.0 |
|eca_resnext26ts.ch_in1k                               |5.854792594909668 |84.224|288.0 |
|convnextv2_atto.fcmae_ft_in1k                         |5.630121231079102 |84.224|288.0 |
|convnext_atto_ols.a2_in1k                             |5.06838321685791  |84.22 |288.0 |
|resnet50c.gluon_in1k                                  |6.173553466796875 |84.216|224.0 |
|res2next50.in1k                                       |10.79014778137207 |84.213|224.0 |
|dla102.in1k                                           |10.784735679626465|84.183|224.0 |
|densenetblur121d.ra_in1k                              |14.575834274291992|84.171|288.0 |
|rexnet_100.nav_in1k                                   |8.324460983276367 |84.158|224.0 |
|inception_v3.tf_in1k                                  |10.925512313842773|84.147|299.0 |
|convnext_atto.d2_in1k                                 |4.6071672439575195|84.141|288.0 |
|res2net50_48w_2s.in1k                                 |6.6574811935424805|84.117|224.0 |
|xcit_tiny_12_p16_224.fb_in1k                          |10.219392776489258|84.111|224.0 |
|tf_efficientnet_lite2.in1k                            |6.47984504699707  |84.085|260.0 |
|poolformer_s12.sail_in1k                              |4.862709045410156 |84.045|224.0 |
|resnet34.a2_in1k                                      |4.931855201721191 |84.045|288.0 |
|efficientnet_b0.ra_in1k                               |6.786894798278809 |84.034|224.0 |
|crossvit_9_dagger_240.in1k                            |8.814949989318848 |84.015|240.0 |
|tf_efficientnet_cc_b0_8e.in1k                         |8.856086730957031 |83.974|224.0 |
|hardcorenas_e.miil_green_in1k                         |7.205872535705566 |83.968|224.0 |
|gmixer_24_224.ra3_in1k                                |7.92539119720459  |83.966|224.0 |
|regnety_016.pycls_in1k                                |18.320565223693848|83.963|224.0 |
|resnext50_32x4d.tv_in1k                               |6.828761100769043 |83.947|224.0 |
|resnet50.gluon_in1k                                   |6.123538017272949 |83.94 |224.0 |
|densenet161.tv_in1k                                   |18.081860542297363|83.91 |224.0 |
|inception_v3.tf_adv_in1k                              |10.756540298461914|83.897|299.0 |
|mobilenetv2_120d.ra_in1k                              |6.804227828979492 |83.897|224.0 |
|resnet101.tv_in1k                                     |10.997323989868164|83.857|224.0 |
|tinynet_a.in1k                                        |7.71148681640625  |83.825|192.0 |
|resnet26d.bt_in1k                                     |4.99755859375     |83.791|288.0 |
|dpn68b.mx_in1k                                        |11.113486289978027|83.788|224.0 |
|hardcorenas_d.miil_green_in1k                         |7.713346481323242 |83.767|224.0 |
|inception_v3.tv_in1k                                  |10.65640926361084 |83.765|299.0 |
|xcit_nano_12_p8_224.fb_dist_in1k                      |10.285968780517578|83.737|224.0 |
|dla60.in1k                                            |6.836915016174316 |83.712|224.0 |
|repvgg_b1g4.rvgg_in1k                                 |7.3067474365234375|83.699|224.0 |
|resnext26ts.ra2_in1k                                  |5.325422286987305 |83.699|288.0 |
|convmixer_1024_20_ks9_p14.in1k                        |7.0061492919921875|83.682|224.0 |
|legacy_seresnet50.in1k                                |8.229660987854004 |83.669|224.0 |
|regnetx_008.tv2_in1k                                  |6.682419776916504 |83.669|224.0 |
|tf_efficientnet_b0.ap_in1k                            |6.905603408813477 |83.652|224.0 |
|skresnet34.ra_in1k                                    |10.816740989685059|83.645|224.0 |
|tf_efficientnet_cc_b0_4e.in1k                         |8.724994659423828 |83.643|224.0 |
|seresnet50.a3_in1k                                    |8.55194091796875  |83.618|224.0 |
|densenet121.ra_in1k                                   |14.188313484191895|83.598|288.0 |
|resmlp_12_224.fb_in1k                                 |3.3252668380737305|83.569|224.0 |
|densenet201.tv_in1k                                   |22.010440826416016|83.554|224.0 |
|mobilenetv3_large_100.miil_in21k_ft_in1k              |5.7849931716918945|83.554|224.0 |
|mixnet_m.ft_in1k                                      |11.25946044921875 |83.532|224.0 |
|legacy_seresnext26_32x4d.in1k                         |5.5554914474487305|83.524|224.0 |
|gernet_s.idstcv_in1k                                  |4.900879859924316 |83.513|224.0 |
|tf_efficientnet_b0.aa_in1k                            |7.207527160644531 |83.502|224.0 |
|hrnet_w18.ms_in1k                                     |29.74583148956299 |83.494|224.0 |
|resnet34.bt_in1k                                      |5.010519027709961 |83.468|288.0 |
|SelecSls42b.in1k                                      |5.212035179138184 |83.449|224.0 |
|efficientformerv2_s0.snap_dist_in1k                   |9.011173248291016 |83.398|224.0 |
|hardcorenas_c.miil_green_in1k                         |5.908851623535156 |83.353|224.0 |
|tf_efficientnet_lite1.in1k                            |6.109323501586914 |83.338|240.0 |
|dpn68.mx_in1k                                         |10.503649711608887|83.195|224.0 |
|tf_mixnet_m.in1k                                      |11.3466215133667  |83.189|224.0 |
|regnetx_016.pycls_in1k                                |7.04801082611084  |83.18 |224.0 |
|tf_efficientnet_es.in1k                               |5.228891372680664 |83.18 |224.0 |
|xcit_nano_12_p16_384.fb_dist_in1k                     |11.523208618164062|83.174|384.0 |
|mobilenetv2_140.ra_in1k                               |4.623532295227051 |83.174|224.0 |
|levit_128s.fb_dist_in1k                               |6.906285285949707 |83.052|224.0 |
|levit_conv_128s.fb_dist_in1k                          |6.290140151977539 |83.046|224.0 |
|repvgg_a2.rvgg_in1k                                   |5.837254524230957 |82.994|224.0 |
|resnet50.tv_in1k                                      |6.108913421630859 |82.96 |224.0 |
|resnet26.bt_in1k                                      |4.607324600219727 |82.917|288.0 |
|hardcorenas_b.miil_green_in1k                         |5.589685440063477 |82.87 |224.0 |
|mobilevitv2_075.cvnets_in1k                           |7.383866310119629 |82.796|256.0 |
|densenet169.tv_in1k                                   |18.422832489013672|82.689|224.0 |
|vit_tiny_r_s16_p8_384.augreg_in21k_ft_in1k            |6.215968132019043 |82.68 |384.0 |
|regnety_004.tv2_in1k                                  |8.67785930633545  |82.642|224.0 |
|edgenext_x_small.in1k                                 |41.36373996734619 |82.58 |288.0 |
|tf_efficientnet_b0.in1k                               |6.9475603103637695|82.563|224.0 |
|mixnet_s.ft_in1k                                      |9.366903305053711 |82.518|224.0 |
|vit_small_patch32_224.augreg_in21k_ft_in1k            |5.148706436157227 |82.516|224.0 |
|regnety_008.pycls_in1k                                |8.240585327148438 |82.482|224.0 |
|efficientnet_lite0.ra_in1k                            |4.374384880065918 |82.373|224.0 |
|resnest14d.gluon_in1k                                 |3.768467903137207 |82.356|224.0 |
|hardcorenas_a.miil_green_in1k                         |4.752740859985352 |82.328|224.0 |
|efficientnet_es_pruned.in1k                           |5.062885284423828 |82.298|224.0 |
|mobilenetv3_rw.rmsp_in1k                              |5.8222150802612305|82.264|224.0 |
|semnasnet_100.rmsp_in1k                               |5.750670433044434 |82.26 |224.0 |
|mobilenetv3_large_100.ra_in1k                         |5.277504920959473 |82.181|224.0 |
|vit_tiny_patch16_224.augreg_in21k_ft_in1k             |5.187463760375977 |82.076|224.0 |
|mobilenetv2_110d.ra_in1k                              |5.811624526977539 |82.076|224.0 |
|tf_mixnet_s.in1k                                      |9.730644226074219 |82.036|224.0 |
|repvgg_b0.rvgg_in1k                                   |6.981081962585449 |82.001|224.0 |
|deit_tiny_distilled_patch16_224.fb_in1k               |5.10258674621582  |81.993|224.0 |
|mixer_b16_224.goog_in21k_ft_in1k                      |5.253963470458984 |81.976|224.0 |
|hrnet_w18_small_v2.ms_in1k                            |15.69828987121582 |81.972|224.0 |
|tf_efficientnet_lite0.in1k                            |4.570498466491699 |81.948|224.0 |
|tinynet_b.in1k                                        |6.75471305847168  |81.88 |188.0 |
|tf_mobilenetv3_large_100.in1k                         |5.984368324279785 |81.843|224.0 |
|pit_ti_distilled_224.in1k                             |14.207158088684082|81.779|224.0 |
|densenet121.tv_in1k                                   |13.54825496673584 |81.732|224.0 |
|regnety_006.pycls_in1k                                |8.096303939819336 |81.715|224.0 |
|regnetx_004_tv.tv2_in1k                               |8.225884437561035 |81.681|224.0 |
|resnet18d.ra2_in1k                                    |3.269658088684082 |81.679|288.0 |
|dla34.in1k                                            |4.496607780456543 |81.666|224.0 |
|xcit_nano_12_p8_224.fb_in1k                           |10.347452163696289|81.647|224.0 |
|crossvit_9_240.in1k                                   |8.11309814453125  |81.615|240.0 |
|fbnetc_100.rmsp_in1k                                  |5.784440040588379 |81.562|224.0 |
|mobilevit_xs.cvnets_in1k                              |7.491569519042969 |81.549|256.0 |
|legacy_seresnet34.in1k                                |6.68367862701416  |81.54 |224.0 |
|regnetx_008.pycls_in1k                                |6.824512481689453 |81.485|224.0 |
|resnet34.gluon_in1k                                   |4.352264404296875 |81.483|224.0 |
|mnasnet_100.rmsp_in1k                                 |4.62559700012207  |81.446|224.0 |
|vgg19_bn.tv_in1k                                      |9.808082580566406 |81.438|224.0 |
|vit_base_patch32_224.augreg_in1k                      |5.228643417358398 |81.143|224.0 |
|convit_tiny.fb_in1k                                   |6.714987754821777 |81.126|224.0 |
|crossvit_tiny_240.in1k                                |9.336371421813965 |81.092|240.0 |
|resnet18.a1_in1k                                      |3.490934371948242 |81.041|288.0 |
|spnasnet_100.rmsp_in1k                                |5.451974868774414 |80.88 |224.0 |
|resnet34.a3_in1k                                      |4.374217987060547 |80.816|224.0 |
|ghostnet_100.in1k                                     |7.456421852111816 |80.705|224.0 |
|regnety_004.pycls_in1k                                |8.646163940429688 |80.652|224.0 |
|skresnet18.ra_in1k                                    |5.625953674316406 |80.648|224.0 |
|regnetx_006.pycls_in1k                                |7.071356773376465 |80.639|224.0 |
|pit_ti_224.in1k                                       |14.267416000366211|80.597|224.0 |
|resnet18.fb_swsl_ig1b_ft_in1k                         |2.7350378036499023|80.586|224.0 |
|vgg16_bn.tv_in1k                                      |8.833065032958984 |80.571|224.0 |
|semnasnet_075.rmsp_in1k                               |5.729928016662598 |80.481|224.0 |
|resnet34.tv_in1k                                      |4.392251968383789 |80.383|224.0 |
|resnet18.a2_in1k                                      |3.19577693939209  |80.306|288.0 |
|mobilenetv2_100.ra_in1k                               |4.749598503112793 |80.253|224.0 |
|xcit_nano_12_p16_224.fb_dist_in1k                     |10.54513931274414 |80.238|224.0 |
|vit_base_patch32_224.sam_in1k                         |5.354809761047363 |80.214|224.0 |
|resnet18.fb_ssl_yfcc100m_ft_in1k                      |3.077993392944336 |80.084|224.0 |
|tf_mobilenetv3_large_075.in1k                         |5.372347831726074 |80.084|224.0 |
|deit_tiny_patch16_224.fb_in1k                         |5.217990875244141 |80.011|224.0 |
|hrnet_w18_small.ms_in1k                               |9.010205268859863 |79.55 |224.0 |
|vgg19.tv_in1k                                         |9.034066200256348 |79.484|224.0 |
|regnetx_004.pycls_in1k                                |7.877168655395508 |79.412|224.0 |
|tf_mobilenetv3_large_minimal_100.in1k                 |4.623851776123047 |79.232|224.0 |
|edgenext_xx_small.in1k                                |22.478294372558594|79.175|288.0 |
|legacy_seresnet18.in1k                                |4.173269271850586 |79.166|224.0 |
|resnet14t.c3_in1k                                     |2.692246437072754 |79.14 |224.0 |
|vgg16.tv_in1k                                         |8.110814094543457 |79.038|224.0 |
|vgg13_bn.tv_in1k                                      |7.848763465881348 |78.995|224.0 |
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k            |5.4071044921875   |78.991|224.0 |
|lcnet_100.ra2_in1k                                    |3.2503747940063477|78.897|224.0 |
|pvt_v2_b0.in1k                                        |5.529088973999023 |78.756|224.0 |
|tinynet_c.in1k                                        |6.2290143966674805|78.444|184.0 |
|resnet18.gluon_in1k                                   |3.228602409362793 |78.372|224.0 |
|mobilevitv2_050.cvnets_in1k                           |6.907343864440918 |78.114|256.0 |
|vgg11_bn.tv_in1k                                      |6.255812644958496 |77.956|224.0 |
|xcit_nano_12_p16_224.fb_in1k                          |10.058245658874512|77.904|224.0 |
|regnety_002.pycls_in1k                                |7.59892463684082  |77.42 |224.0 |
|resnet18.tv_in1k                                      |2.8421449661254883|77.287|224.0 |
|mixer_l16_224.goog_in21k_ft_in1k                      |16.1234712600708  |77.279|224.0 |
|vgg13.tv_in1k                                         |7.092685699462891 |77.227|224.0 |
|mobilevit_xxs.cvnets_in1k                             |7.4790191650390625|76.604|256.0 |
|resnet18.a3_in1k                                      |2.994236946105957 |76.454|224.0 |
|vgg11.tv_in1k                                         |5.845661163330078 |76.384|224.0 |
|resnet10t.c3_in1k                                     |2.4929332733154297|76.173|224.0 |
|regnetx_002.pycls_in1k                                |5.758271217346191 |76.124|224.0 |
|lcnet_075.ra2_in1k                                    |3.240180015563965 |76.036|224.0 |
|dla60x_c.in1k                                         |5.504012107849121 |75.622|224.0 |
|mobilenetv3_small_100.lamb_in1k                       |4.730005264282227 |74.913|224.0 |
|tf_mobilenetv3_small_100.in1k                         |4.762835502624512 |74.721|224.0 |
|tinynet_d.in1k                                        |4.560756683349609 |74.29 |152.0 |
|mnasnet_small.lamb_in1k                               |5.298247337341309 |73.801|224.0 |
|dla46x_c.in1k                                         |4.563655853271484 |73.649|224.0 |
|mobilenetv2_050.lamb_in1k                             |4.5906782150268555|73.463|224.0 |
|tf_mobilenetv3_small_075.in1k                         |4.9480438232421875|72.804|224.0 |
|dla46_c.in1k                                          |4.773392677307129 |72.622|224.0 |
|mobilenetv3_small_075.lamb_in1k                       |4.622502326965332 |72.312|224.0 |
|lcnet_050.ra2_in1k                                    |2.962799072265625 |70.423|224.0 |
|tf_mobilenetv3_small_minimal_100.in1k                 |3.5083532333374023|70.098|224.0 |
|tinynet_e.in1k                                        |3.923039436340332 |66.806|106.0 |
|mobilenetv3_small_050.lamb_in1k                       |4.597330093383789 |64.695|224.0 |
