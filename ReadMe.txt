User guide : https://docs.rendercv.com/user_guide/

rendercv new "Alexandre_Movsessian_CV" --theme "engineeringresumes"

rendercv render CV_FR/Alexandre_Movsessian_FR_CV.yaml --output-folder-name CV_FR/rendercv_output --watch
rendercv render CV_ENG/Alexandre_Movsessian_ENG_CV.yaml --output-folder-name CV_ENG/rendercv_output --watch

rendercv does not let you choose your output filename for some bs reason.