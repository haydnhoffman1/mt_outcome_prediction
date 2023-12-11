# mt_outcome_prediction
Mortality and disability prediction after mechanical thrombectomy

Python notebooks and models for:

Development and internal validation of machine learning models to predict mortality and disability after mechanical thrombectomy for acute anterior circulation large vessel occlusion
Haydn Hoffman M.D., Jacob Wood B.S., John R Cote B.S., Muhammad S Jalal M.D., Fadar O Otite M.D., Hesham E Masoud M.D., Grahame C Gould M.D.


Models are organized by outcome they predict:
dsd = death/severe disability (mRS 4-6) @ 90 days
fav_functional_status = favorable functional status (mRS 0-2) @ 90 days
mortality = mortality (mRS 6) @ 90 days

And further organized by whether or not they incorporate features from the thrombectomy procedure:
no_mt_data = only pre-procedural data incorporated in model
mt_data = incorporates procedural data from thrombectomy (i.e. # passes, TICI, etc.)

Questions/comments:
hhoffman@semmes-murphey.com
