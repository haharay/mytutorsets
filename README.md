# mytutorsets
打开计时考试，监考考试部分因为需要额外的第三方支持以及https等建议暂时不去做。
计时考试在手机上的操作页还算界面友好，基本上支持还是不错的。
注意在考试前需要设定每个部分是否可见、尝试次数（advanced设置）。





### 安装
tutor plugins install https://raw.githubusercontent.com/haharay/mytutorsets/main/mytutorsets.yml

tutor plugins list
tutor plugins enable TimedExam
tutor config save
tutor local quickstart

sudo curl -L "https://github.com/overhangio/tutor/releases/download/v10.3.0/tutor-$(uname -s)_$(uname -m)" -o /usr/local/bin/tutor