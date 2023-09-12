这个文件夹是用于做宇宙线探测性能实验的

text_file_list.txt  数据文件路径列表，需更改
CSST*_L0.1.fits     宇宙线仿真图像
CSST*_flg.fits      宇宙线标记图像
CSST*_flg.fits.sixteen  宇宙线标记图像中提取标记16后的0/1图
CSST*_check.fits    仿真*标记之后的检查图像，可以认为是探测到的宇宙线

cmr_check.ipynb     主程序，其中只有config_path需要更改，为程序和文件路径列表和配置文件的所在目录

cmr.sex cmr.param   SExtrator的配置文件
cmr.acat            无意义
/acat               SExtractor生成的目标星表，以及各种reg文件

