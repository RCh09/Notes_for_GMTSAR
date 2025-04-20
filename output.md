rajashree@Santanu:~/S1A_SLC_TOPS_LA$ ll
total 36
drwxr-xr-x  4 rajashree rajashree 4096 Apr 19 23:58 ./
drwxr-x--- 14 rajashree rajashree 4096 Apr 19 23:38 ../
-rw-r--r--  1 rajashree rajashree 6148 Aug 20  2019 .DS_Store
-rwxr-xr-x  1 rajashree rajashree  210 Aug 22  2019 ._.*
-rwxr-xr-x  1 rajashree rajashree 1262 Jul 27  2021 README.txt*
-rw-r--r--  1 rajashree rajashree  141 Apr 20  2022 README_prep.txt
drwxr-xr-x  4 rajashree rajashree 4096 Aug 18  2017 raw/
drwxr-xr-x  2 rajashree rajashree 4096 Apr 19 20:37 topo/
rajashree@Santanu:~/S1A_SLC_TOPS_LA$ pop_config.csh S1_TOPS > config.txt
rajashree@Santanu:~/S1A_SLC_TOPS_LA$ p2p_S1_TOPS_Frame.csh S1A_IW_SLC__1SSV_20150526T014935_20150526T015002_006086_007E23_679A.SAFE S1A_OPER_AUX_POEORB_OPOD_20150615T155109_V20150525T225944_20150527T005944.EOF S1A_IW_SLC__1SDV_20150607T014936_20150607T015003_006261_00832E_3626.SAFE S1A_OPER_AUX_POEORB_OPOD_20150627T155155_V20150606T225944_20150608T005944.EOF config.txt vv 0
vv
0
Linking files for Subswath 1 ...
ln: failed to create symbolic link './s1a-iw1-slc-vv-20150526t014935-20150526t015000-006086-007e23-001.tiff': File exists
ln: failed to create symbolic link './s1a-iw1-slc-vv-20150607t014936-20150607t015001-006261-00832e-004.tiff': File exists
Linking files for Subswath 2 ...
ln: failed to create symbolic link './s1a-iw2-slc-vv-20150526t014936-20150526t015001-006086-007e23-002.tiff': File exists
ln: failed to create symbolic link './s1a-iw2-slc-vv-20150607t014936-20150607t015002-006261-00832e-005.tiff': File exists
Linking files for Subswath 3 ...
ln: failed to create symbolic link './s1a-iw3-slc-vv-20150526t014937-20150526t015002-006086-007e23-003.tiff': File exists
ln: failed to create symbolic link './s1a-iw3-slc-vv-20150607t014937-20150607t015003-006261-00832e-006.tiff': File exists


PREPROCESS - START

Working on images s1a-iw1-slc-vv-20150526t014935-20150526t015000-006086-007e23-001 s1a-iw1-slc-vv-20150607t014936-20150607t015001-006261-00832e-004 ...
rm: No match.
rm: No match.
pre_proc.csh S1_TOPS s1a-iw1-slc-vv-20150526t014935-20150526t015000-006086-007e23-001 s1a-iw1-slc-vv-20150607t014936-20150607t015001-006261-00832e-004  -skip_master 0
pre_proc.csh

 Pre-Process S1_TOPS data - START

ln: failed to create symbolic link './dem.grd': File exists
S1_20150526_014935_F1
S1_20150607_014936_F1
Reading in 5004 lines of info from XML...
Writing 31 lines for orbit...
Reading in 4939 lines of info from XML...
Writing 31 lines for orbit...
Writing 282 lines of precise orbit for the LED file...
Successfully opened S1_20150526_014935_F1.PRM
Writing 282 lines of precise orbit for the LED file...
Successfully opened S1_20150607_014936_F1.PRM
using command line
......master LED file S1_20150526_014935_F1.LED
.........aligned LED file S1_20150607_014936_F1.LED
using command line
......master LED file S1_20150526_014935_F1.LED
.........aligned LED file S1_20150607_014936_F1.LED
[1] 2406
[2] 2407
[2]    Done                   SAT_llt2rat S1_20150607_014936_F1.PRM 1 < topo.llt > aligned.ratll
[1]  + Done                   SAT_llt2rat S1_20150526_014935_F1.PRM 1 < topo.llt > master.ratll
blockmedian [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
blockmedian [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
blockmedian (gmtapi_init_grdheader): Please select compatible -R and -I values
blockmedian [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
blockmedian [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
blockmedian (gmtapi_init_grdheader): Please select compatible -R and -I values
[1] 2419
[2] 2420
surface [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface [WARNING]: Your grid dimensions are mutually prime.  Convergence is very unlikely.
surface [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface [WARNING]: Your grid dimensions are mutually prime.  Convergence is very unlikely.
[2]  + Done                   gmt surface atmp.xyz -bi3d -R0/20664/0/12196 -I16/8 -T0.3 -Gatmp.grd -N1000 -r
[1]  + Done                   gmt surface rtmp.xyz -bi3d -R0/20664/0/12196 -I16/8 -T0.3 -Grtmp.grd -N1000 -r
Reading in 5004 lines of info from XML...
Writing 31 lines for orbit...
Writing SLC..Image Size: 21928 X 12196...
Working on burst  #1 #2 #3 #4 #5 #6 #7 #8 #9
number of points clipped to short int 14
Reading in 4939 lines of info from XML...
Writing 31 lines for orbit...
Reading in range and azimuth shifts table...
Writing SLC..Image Size: 20664 X 12196...
Working on burst  #1 #2 #3 #4 #5 #6 #7 #8 #9
number of points clipped to short int 47
Writing 282 lines of precise orbit for the LED file...
Writing 282 lines of precise orbit for the LED file...
Successfully opened S1_20150526_014935_F1.PRM
Successfully opened S1_20150607_014936_F1.PRM

 Pre-Process S1_TOPS data - END


PREPROCESS - END

rm: No match.
rm: No match.

ALIGN.CSH - START


ALIGN.CSH - END


clean up topo/ folder


DEM2TOPO_RA.CSH - START
USER SHOULD PROVIDE DEM FILE
Working over 0/21928/0/12196 ...
 range decimation is:  2
blockmedian [INFORMATION]: Provides 3, expects 3-column binary data
blockmedian [INFORMATION]: Processing input table data
blockmedian [INFORMATION]: W: 0 E: 21928 S: 0 N: 12196 n_columns: 10964 n_rows: 6098
blockmedian [INFORMATION]: Input 3 columns via binary records using format ddd
blockmedian [INFORMATION]: Output 3 columns via binary records using format ddd
blockmedian [INFORMATION]: Reading Data Table from Standard Input stream
blockmedian [INFORMATION]: Writing Data Table to Standard Output stream
blockmedian [INFORMATION]: Calculating block medians
blockmedian [INFORMATION]: N read: 2072117 N used: 2066028 outside_area: 6089 N cells filled: 2065906
surface [INFORMATION]: Provides 3, expects 3-column binary data
surface [INFORMATION]: Internally speed up convergence by using the larger region -R-557/22483/-47/12241 (go from 10964 x 6098 to optimal 11520 x 6144, with speedup-factor 486.17364)
surface [INFORMATION]: Grid domain: W: 0 E: 21928 S: 0 N: 12196 n_columns: 11520 n_rows: 6144 [pixel registration]
surface [INFORMATION]: Processing input table data
surface [INFORMATION]: Input 3 columns via binary records using format ddd
surface [INFORMATION]: Reading Data Table from file temp.rat
surface [INFORMATION]: Minimum value of your dataset x,y,z at: 7265.97265625 11693.5625 -535.137390137
surface [INFORMATION]: Maximum value of your dataset x,y,z at: 2794.16088867 2781.82080078 465.222869873
surface [INFORMATION]: Eliminate data points that are not nearest a node.
surface [WARNING]: 93 unusable points were supplied; these will be ignored.
surface [WARNING]: You should have pre-processed the data with block-mean, -median, or -mode.
surface [WARNING]: Check that previous processing steps write results with enough decimals.
surface [WARNING]: Possibly some data were half-way between nodes and subject to IEEE 754 rounding.
surface [INFORMATION]: Plane fit z = -35.3354 + (-0.00243702 * col) + (-0.0721217 * row)
surface [INFORMATION]: Normalize detrended data constraints by z rms = 59.3182
surface [INFORMATION]: Select default convergence limit of 0.00593182 (100 ppm of L2 scale)
surface [INFORMATION]: Recompute data index for next iteration [stride = 768]
surface [INFORMATION]: ------------------------------------------
surface [INFORMATION]: Memory for data array          :   47.3 Mb
surface [INFORMATION]: Memory for final grid          :  270.3 Mb
surface [INFORMATION]: Memory for Briggs coefficients :   47.3 Mb
surface [INFORMATION]: Memory for node status         :   67.6 Mb
surface [INFORMATION]: ------------------------------------------
surface [INFORMATION]: Total memory use               :  432.5 Mb
surface [INFORMATION]: ==========================================
surface [INFORMATION]: Grid     Mode    Iteration       Max Change      Conv Limit      Total Iterations
surface [INFORMATION]: Set finite-difference coefficients [stride = 768]
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 768]
surface [INFORMATION]:  768     D            183        7.0078677402e-06        7.72372209699e-06           183
surface [INFORMATION]: Recompute data index for next iteration [stride = 256]
surface [INFORMATION]: Expand grid by factor of 3 when going from stride = 768 to 256
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 256]
surface [INFORMATION]:  256     I             67        1.77550586458e-05       2.3171166291e-05            250
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 256]
surface [INFORMATION]:  256     D         256000        3.63055068434e-05       2.3171166291e-05         256250
surface [INFORMATION]: Recompute data index for next iteration [stride = 128]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 256 to 128
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 128]
surface [INFORMATION]:  128     I             38        3.72856231667e-05       4.6342332582e-05         256288
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 128]
surface [INFORMATION]:  128     D             24        3.3532849408e-05        4.6342332582e-05         256312
surface [INFORMATION]: Recompute data index for next iteration [stride = 64]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 128 to 64
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 64]
surface [INFORMATION]:   64     I             38        6.68504860429e-05       9.26846651639e-05        256350
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 64]
surface [INFORMATION]:   64     D             24        8.62801695439e-05       9.26846651639e-05        256374
surface [INFORMATION]: Recompute data index for next iteration [stride = 32]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 64 to 32
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 32]
surface [INFORMATION]:   32     I             35        0.000166332617759       0.000185369330328        256409
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 32]
surface [INFORMATION]:   32     D          10020        0.000185029232571       0.000185369330328        266429
surface [INFORMATION]: Recompute data index for next iteration [stride = 16]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 32 to 16
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 16]
surface [INFORMATION]:   16     I             32        0.000316779838322       0.000370738660656        266461
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 16]
surface [INFORMATION]:   16     D          16000        0.000571228660154       0.000370738660656        282461
surface [INFORMATION]: Recompute data index for next iteration [stride = 8]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 16 to 8
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 8]
surface [INFORMATION]:    8     I             30        0.000674221451155       0.000741477321311        282491
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 8]
surface [INFORMATION]:    8     D           8000        0.0027513884544 0.000741477321311       290491
surface [INFORMATION]: Recompute data index for next iteration [stride = 4]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 8 to 4
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 4]
surface [INFORMATION]:    4     I             27        0.00132291328008        0.00148295464262         290518
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 4]
surface [INFORMATION]:    4     D           4000        0.00673659207662        0.00148295464262         294518
surface [INFORMATION]: Recompute data index for next iteration [stride = 2]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 4 to 2
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 2]
surface [INFORMATION]:    2     I             24        0.00246327227523        0.00296590928525         294542
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 2]
surface [INFORMATION]:    2     D           2000        0.00567774494161        0.00296590928525         296542
surface [INFORMATION]: Recompute data index for next iteration [stride = 1]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 2 to 1
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 1]
surface [INFORMATION]:    1     I             19        0.00490534608657        0.00593181857049         296561
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 1]
surface [INFORMATION]:    1     D           1000        0.0282436712588 0.00593181857049        297561
surface [INFORMATION]: Compute rms misfit and curvature.
surface [INFORMATION]: Fit info: N data points  N nodes mean error      rms error       curvature
surface [INFORMATION]:   2065813        70796545        1.90807643518e-06       0.00896612579665     112897.527602
surface [INFORMATION]: Increase pad by 278 278 23 23
surface [INFORMATION]: Writing grid to file pixel.grd
grd2cpt [INFORMATION]: Reading CPT from File /usr/local/share/cpt/gmt/gray.cpt
grd2cpt [INFORMATION]: Processing input grid(s)
grd2cpt [INFORMATION]: netCDF grid topo_ra.grd has no default CPT.
grd2cpt [INFORMATION]: Reading grid from file topo_ra.grd
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for all edges: natural
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for left   edge: natural
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for right  edge: natural
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for bottom edge: natural
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for top    edge: natural
grd2cpt [INFORMATION]: Mean and S.D. of data are -272.096136113 141.141448448
grd2cpt [INFORMATION]: z = -596.225891113 and CDF(z) = 0
grd2cpt [INFORMATION]: z = -452.976180335 and CDF(z) = 0.0920130375102
grd2cpt [INFORMATION]: z = -390.883776064 and CDF(z) = 0.259161729858
grd2cpt [INFORMATION]: z = -346.110784043 and CDF(z) = 0.368043908752
grd2cpt [INFORMATION]: z = -307.853913209 and CDF(z) = 0.446890626619
grd2cpt [INFORMATION]: z = -272.096136113 and CDF(z) = 0.514651942908
grd2cpt [INFORMATION]: z = -236.338359016 and CDF(z) = 0.58864771227
grd2cpt [INFORMATION]: z = -198.081488182 and CDF(z) = 0.667607923609
grd2cpt [INFORMATION]: z = -153.308496162 and CDF(z) = 0.757098259097
grd2cpt [INFORMATION]: z = -91.2160918908 and CDF(z) = 0.877656116306
grd2cpt [INFORMATION]: z = 465.137908936 and CDF(z) = 1
grd2cpt [INFORMATION]: Write CPT to Stream Standard output stream
grdimage [INFORMATION]: GMT_Parse_Options: Interval-setting -B options were reordered to appear before axis and frame -B options to ensure proper parsing.
grdimage [INFORMATION]: GMT_Parse_Options: New option order: topo_ra.grd -JX7i -P -Ctopo_ra.cpt -V -K -Bxaf+lRange -B"yaf+lReversed Azimuth" -BWSen
grdimage [INFORMATION]: Read header from file topo_ra.grd
grdimage [INFORMATION]: netCDF grid topo_ra.grd has no default CPT.
grdimage [INFORMATION]: Linear projection implies y-axis distance exaggeration relative to the x-axis by a factor of 1.79797
grdimage [INFORMATION]: Auto-frame interval for x-axis (item 0): a5000f1000
grdimage [INFORMATION]: Auto-frame interval for y-axis (item 0): a2000f1000
grdimage [INFORMATION]: Map scale is 1.2333 km per cm or 1:123330.
grdimage [INFORMATION]: Allocate and read data from file topo_ra.grd
grdimage [INFORMATION]: Reading grid from file topo_ra.grd
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for all edges: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for left   edge: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for right  edge: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for bottom edge: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for top    edge: natural
grdimage [INFORMATION]: gmt_cpt_default: Use specific CPT: topo_ra.cpt
grdimage [INFORMATION]: Reading CPT from File topo_ra.cpt
grdimage [INFORMATION]: Evaluate image pixel colors
grdimage [INFORMATION]: Basic z(x,y) -> gray image with no illumination.
grdimage [INFORMATION]: Plotting 8-bit grayshade image
PSL: DEFLATE compressed 66858472 to 3418154 bytes (94.9% savings at compression level 5)
Topo range/azimuth map: topo_ra.pdf
DEM2TOPO_RA.CSH - END
NO TOPO_RA SHIFT

INTF.CSH, FILTER.CSH - START
using command line
......master LED file S1_20150526_014935_F1.LED
.........aligned LED file S1_20150607_014936_F1.LED
using command line
......master LED file S1_20150526_014935_F1.LED
.........aligned LED file S1_20150526_014935_F1.LED
intf.csh
running phasediff...
reading topo topo_ra.grd
 xdim 21928, ydim 12196
filter.csh
setting range_dec = 8, azimuth_dec = 2
gauss_200 2 4 (1 2)
making amplitudes...
filtering interferogram...
making amplitude...
making correlation...
making phase...
filtering phase...
INTF.CSH, FILTER.CSH - END

SKIP UNWRAP PHASE

SKIP GEOCODE



PREPROCESS - START

Working on images s1a-iw2-slc-vv-20150526t014936-20150526t015001-006086-007e23-002 s1a-iw2-slc-vv-20150607t014936-20150607t015002-006261-00832e-005 ...
rm: No match.
rm: No match.
pre_proc.csh S1_TOPS s1a-iw2-slc-vv-20150526t014936-20150526t015001-006086-007e23-002 s1a-iw2-slc-vv-20150607t014936-20150607t015002-006261-00832e-005  -skip_master 0
pre_proc.csh

 Pre-Process S1_TOPS data - START

ln: failed to create symbolic link './dem.grd': File exists
S1_20150526_014936_F2
S1_20150607_014936_F2
Reading in 5004 lines of info from XML...
Writing 31 lines for orbit...
Reading in 4939 lines of info from XML...
Writing 31 lines for orbit...
Writing 282 lines of precise orbit for the LED file...
Successfully opened S1_20150526_014936_F2.PRM
Writing 282 lines of precise orbit for the LED file...
Successfully opened S1_20150607_014936_F2.PRM
using command line
......master LED file S1_20150526_014936_F2.LED
.........aligned LED file S1_20150607_014936_F2.LED
using command line
......master LED file S1_20150526_014936_F2.LED
.........aligned LED file S1_20150607_014936_F2.LED
[1] 2833
[2] 2834
[2]    Done                   SAT_llt2rat S1_20150607_014936_F2.PRM 1 < topo.llt > aligned.ratll
[1]  + Done                   SAT_llt2rat S1_20150526_014936_F2.PRM 1 < topo.llt > master.ratll
blockmedian [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
blockmedian (gmtapi_init_grdheader): Please select compatible -R and -I values
blockmedian [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
blockmedian (gmtapi_init_grdheader): Please select compatible -R and -I values
[1] 2846
[2] 2847
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
[2]    Done                   gmt surface atmp.xyz -bi3d -R0/24640/0/12196 -I16/8 -T0.3 -Gatmp.grd -N1000 -r
[1]  + Done                   gmt surface rtmp.xyz -bi3d -R0/24640/0/12196 -I16/8 -T0.3 -Grtmp.grd -N1000 -r
Reading in 5004 lines of info from XML...
Writing 31 lines for orbit...
Writing SLC..Image Size: 25788 X 12192...
Working on burst  #1 #2 #3 #4 #5 #6 #7 #8 #9
number of points clipped to short int 6
Reading in 4939 lines of info from XML...
Writing 31 lines for orbit...
Reading in range and azimuth shifts table...
Writing SLC..Image Size: 24640 X 12196...
Working on burst  #1 #2 #3 #4 #5 #6 #7 #8 #9
number of points clipped to short int 9
Writing 282 lines of precise orbit for the LED file...
Writing 282 lines of precise orbit for the LED file...
Successfully opened S1_20150526_014936_F2.PRM
Successfully opened S1_20150607_014936_F2.PRM

 Pre-Process S1_TOPS data - END


PREPROCESS - END

rm: No match.
rm: No match.

ALIGN.CSH - START


ALIGN.CSH - END


clean up topo/ folder


DEM2TOPO_RA.CSH - START
USER SHOULD PROVIDE DEM FILE
Working over 0/25788/0/12192 ...
 range decimation is:  2
blockmedian [INFORMATION]: Provides 3, expects 3-column binary data
blockmedian [INFORMATION]: Processing input table data
blockmedian [INFORMATION]: W: 0 E: 25788 S: 0 N: 12192 n_columns: 12894 n_rows: 6096
blockmedian [INFORMATION]: Input 3 columns via binary records using format ddd
blockmedian [INFORMATION]: Output 3 columns via binary records using format ddd
blockmedian [INFORMATION]: Reading Data Table from Standard Input stream
blockmedian [INFORMATION]: Writing Data Table to Standard Output stream
blockmedian [INFORMATION]: Calculating block medians
blockmedian [INFORMATION]: N read: 2297438 N used: 2288211 outside_area: 9227 N cells filled: 2287855
surface [INFORMATION]: Provides 3, expects 3-column binary data
surface [INFORMATION]: Internally speed up convergence by using the larger region -R-67/25853/-49/12239 (go from 12894 x 6096 to optimal 12960 x 6144, with speedup-factor 22.98633)
surface [INFORMATION]: Grid domain: W: 0 E: 25788 S: 0 N: 12192 n_columns: 12960 n_rows: 6144 [pixel registration]
surface [INFORMATION]: Processing input table data
surface [INFORMATION]: Input 3 columns via binary records using format ddd
surface [INFORMATION]: Reading Data Table from file temp.rat
surface [INFORMATION]: Minimum value of your dataset x,y,z at: 739.96661377 11448.1376953 -454.68371582
surface [INFORMATION]: Maximum value of your dataset x,y,z at: 25204.2421875 10170.4462891 2762.07617188
surface [INFORMATION]: Eliminate data points that are not nearest a node.
surface [WARNING]: 325 unusable points were supplied; these will be ignored.
surface [WARNING]: You should have pre-processed the data with block-mean, -median, or -mode.
surface [WARNING]: Check that previous processing steps write results with enough decimals.
surface [WARNING]: Possibly some data were half-way between nodes and subject to IEEE 754 rounding.
surface [INFORMATION]: Plane fit z = -475.194 + (0.0737802 * col) + (0.0458915 * row)
surface [INFORMATION]: Normalize detrended data constraints by z rms = 308.316
surface [INFORMATION]: Select default convergence limit of 0.0308316 (100 ppm of L2 scale)
surface [INFORMATION]: Recompute data index for next iteration [stride = 96]
surface [INFORMATION]: ------------------------------------------
surface [INFORMATION]: Memory for data array          :   52.4 Mb
surface [INFORMATION]: Memory for final grid          :  304.1 Mb
surface [INFORMATION]: Memory for Briggs coefficients :   52.4 Mb
surface [INFORMATION]: Memory for node status         :   76.0 Mb
surface [INFORMATION]: ------------------------------------------
surface [INFORMATION]: Total memory use               :  484.9 Mb
surface [INFORMATION]: ==========================================
surface [INFORMATION]: Grid     Mode    Iteration       Max Change      Conv Limit      Total Iterations
surface [INFORMATION]: Set finite-difference coefficients [stride = 96]
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 96]
surface [INFORMATION]:   96     D             20        0.00018183301526        0.000321162207905            20
surface [INFORMATION]: Recompute data index for next iteration [stride = 32]
surface [INFORMATION]: Expand grid by factor of 3 when going from stride = 96 to 32
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 32]
surface [INFORMATION]:   32     I             52        0.000750582599104       0.000963486623716            72
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 32]
surface [INFORMATION]:   32     D             35        0.000949973580045       0.000963486623716           107
surface [INFORMATION]: Recompute data index for next iteration [stride = 16]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 32 to 16
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 16]
surface [INFORMATION]:   16     I             30        0.0012970201536 0.00192697324743           137
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 16]
surface [INFORMATION]:   16     D            217        0.00191756515711        0.00192697324743            354
surface [INFORMATION]: Recompute data index for next iteration [stride = 8]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 16 to 8
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 8]
surface [INFORMATION]:    8     I             27        0.00288599568627        0.00385394649486            381
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 8]
surface [INFORMATION]:    8     D           1004        0.00384883320077        0.00385394649486           1385
surface [INFORMATION]: Recompute data index for next iteration [stride = 4]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 8 to 4
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 4]
surface [INFORMATION]:    4     I             24        0.00543752908196        0.00770789298973           1409
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 4]
surface [INFORMATION]:    4     D           2366        0.00770221072622        0.00770789298973           3775
surface [INFORMATION]: Recompute data index for next iteration [stride = 2]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 4 to 2
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 2]
surface [INFORMATION]:    2     I             20        0.00984202831322        0.0154157859795            3795
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 2]
surface [INFORMATION]:    2     D           1252        0.0154140694032 0.0154157859795       5047
surface [INFORMATION]: Recompute data index for next iteration [stride = 1]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 2 to 1
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 1]
surface [INFORMATION]:    1     I             15        0.0245852155791 0.0308315719589       5062
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 1]
surface [INFORMATION]:    1     D           1000        0.0319431063261 0.0308315719589       6062
surface [INFORMATION]: Compute rms misfit and curvature.
surface [INFORMATION]: Fit info: N data points  N nodes mean error      rms error       curvature
surface [INFORMATION]:   2287530        79645345        -2.29174725793e-07      0.00278031608796     32754.7494181
surface [INFORMATION]: Increase pad by 33 33 24 24
surface [INFORMATION]: Writing grid to file pixel.grd
grd2cpt [INFORMATION]: Reading CPT from File /usr/local/share/cpt/gmt/gray.cpt
grd2cpt [INFORMATION]: Processing input grid(s)
grd2cpt [INFORMATION]: netCDF grid topo_ra.grd has no default CPT.
grd2cpt [INFORMATION]: Reading grid from file topo_ra.grd
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for all edges: natural
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for left   edge: natural
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for right  edge: natural
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for bottom edge: natural
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for top    edge: natural
grd2cpt [INFORMATION]: Mean and S.D. of data are 142.766650733 422.313057299
grd2cpt [INFORMATION]: z = -464.439605713 and CDF(z) = 0
grd2cpt [INFORMATION]: z = -398.449308999 and CDF(z) = 0.00030486570267
grd2cpt [INFORMATION]: z = -212.660985505 and CDF(z) = 0.148700088037
grd2cpt [INFORMATION]: z = -78.6945330383 and CDF(z) = 0.380412640048
grd2cpt [INFORMATION]: z = 35.7748610495 and CDF(z) = 0.51752624109
grd2cpt [INFORMATION]: z = 142.766650733 and CDF(z) = 0.639293035226
grd2cpt [INFORMATION]: z = 249.758440416 and CDF(z) = 0.709003657587
grd2cpt [INFORMATION]: z = 364.227834504 and CDF(z) = 0.783333447622
grd2cpt [INFORMATION]: z = 498.194286971 and CDF(z) = 0.835248299521
grd2cpt [INFORMATION]: z = 683.982610465 and CDF(z) = 0.889439434503
grd2cpt [INFORMATION]: z = 2761.56079102 and CDF(z) = 1
grd2cpt [INFORMATION]: Write CPT to Stream Standard output stream
grdimage [INFORMATION]: GMT_Parse_Options: Interval-setting -B options were reordered to appear before axis and frame -B options to ensure proper parsing.
grdimage [INFORMATION]: GMT_Parse_Options: New option order: topo_ra.grd -JX7i -P -Ctopo_ra.cpt -V -K -Bxaf+lRange -B"yaf+lReversed Azimuth" -BWSen
grdimage [INFORMATION]: Read header from file topo_ra.grd
grdimage [INFORMATION]: netCDF grid topo_ra.grd has no default CPT.
grdimage [INFORMATION]: Linear projection implies y-axis distance exaggeration relative to the x-axis by a factor of 2.11516
grdimage [INFORMATION]: Auto-frame interval for x-axis (item 0): a5000f1000
grdimage [INFORMATION]: Auto-frame interval for y-axis (item 0): a2000f1000
grdimage [INFORMATION]: Map scale is 1.45039 km per cm or 1:145039.
grdimage [INFORMATION]: Allocate and read data from file topo_ra.grd
grdimage [INFORMATION]: Reading grid from file topo_ra.grd
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for all edges: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for left   edge: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for right  edge: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for bottom edge: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for top    edge: natural
grdimage [INFORMATION]: gmt_cpt_default: Use specific CPT: topo_ra.cpt
grdimage [INFORMATION]: Reading CPT from File topo_ra.cpt
grdimage [INFORMATION]: Evaluate image pixel colors
grdimage [INFORMATION]: Basic z(x,y) -> gray image with no illumination.
grdimage [INFORMATION]: Plotting 8-bit grayshade image
PSL: DEFLATE compressed 78601824 to 11455049 bytes (85.4% savings at compression level 5)
Topo range/azimuth map: topo_ra.pdf
DEM2TOPO_RA.CSH - END
NO TOPO_RA SHIFT

INTF.CSH, FILTER.CSH - START
using command line
......master LED file S1_20150526_014936_F2.LED
.........aligned LED file S1_20150607_014936_F2.LED
using command line
......master LED file S1_20150526_014936_F2.LED
.........aligned LED file S1_20150526_014936_F2.LED
intf.csh
running phasediff...
reading topo topo_ra.grd
 xdim 25788, ydim 12192
filter.csh
setting range_dec = 8, azimuth_dec = 2
gauss_200 2 4 (1 2)
making amplitudes...
filtering interferogram...
making amplitude...
making correlation...
making phase...
filtering phase...
INTF.CSH, FILTER.CSH - END

SKIP UNWRAP PHASE

SKIP GEOCODE



PREPROCESS - START

Working on images s1a-iw3-slc-vv-20150526t014937-20150526t015002-006086-007e23-003 s1a-iw3-slc-vv-20150607t014937-20150607t015003-006261-00832e-006 ...
rm: No match.
rm: No match.
pre_proc.csh S1_TOPS s1a-iw3-slc-vv-20150526t014937-20150526t015002-006086-007e23-003 s1a-iw3-slc-vv-20150607t014937-20150607t015003-006261-00832e-006  -skip_master 0
pre_proc.csh

 Pre-Process S1_TOPS data - START

ln: failed to create symbolic link './dem.grd': File exists
S1_20150526_014937_F3
S1_20150607_014937_F3
Reading in 5004 lines of info from XML...
Writing 31 lines for orbit...
Reading in 4939 lines of info from XML...
Writing 31 lines for orbit...
Writing 282 lines of precise orbit for the LED file...
Successfully opened S1_20150526_014937_F3.PRM
Writing 282 lines of precise orbit for the LED file...
Successfully opened S1_20150607_014937_F3.PRM
using command line
......master LED file S1_20150526_014937_F3.LED
.........aligned LED file S1_20150607_014937_F3.LED
using command line
......master LED file S1_20150526_014937_F3.LED
.........aligned LED file S1_20150607_014937_F3.LED
[1] 3232
[2] 3233
[2]    Done                   SAT_llt2rat S1_20150607_014937_F3.PRM 1 < topo.llt > aligned.ratll
[1]  + Done                   SAT_llt2rat S1_20150526_014937_F3.PRM 1 < topo.llt > master.ratll
blockmedian [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
blockmedian [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
blockmedian (gmtapi_init_grdheader): Please select compatible -R and -I values
blockmedian [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
blockmedian [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
blockmedian (gmtapi_init_grdheader): Please select compatible -R and -I values
[1] 3245
[2] 3246
surface [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
surface [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
surface [WARNING]: (x_max-x_min) must equal (NX + eps) * x_inc), where NX is an integer and |eps| <= 0.0001.
surface [WARNING]: (y_max-y_min) must equal (NY + eps) * y_inc), where NY is an integer and |eps| <= 0.0001.
surface (gmtapi_init_grdheader): Please select compatible -R and -I values
[2]    Done                   gmt surface atmp.xyz -bi3d -R0/23848/0/12196 -I16/8 -T0.3 -Gatmp.grd -N1000 -r
[1]  + Done                   gmt surface rtmp.xyz -bi3d -R0/23848/0/12196 -I16/8 -T0.3 -Grtmp.grd -N1000 -r
Reading in 5004 lines of info from XML...
Writing 31 lines for orbit...
Writing SLC..Image Size: 24864 X 12196...
Working on burst  #1 #2 #3 #4 #5 #6 #7 #8 #9
number of points clipped to short int 0
Reading in 4939 lines of info from XML...
Writing 31 lines for orbit...
Reading in range and azimuth shifts table...
Writing SLC..Image Size: 23848 X 12196...
Working on burst  #1 #2 #3 #4 #5 #6 #7 #8 #9
number of points clipped to short int 1
Writing 282 lines of precise orbit for the LED file...
Writing 282 lines of precise orbit for the LED file...
Successfully opened S1_20150526_014937_F3.PRM
Successfully opened S1_20150607_014937_F3.PRM

 Pre-Process S1_TOPS data - END


PREPROCESS - END

rm: No match.
rm: No match.

ALIGN.CSH - START


ALIGN.CSH - END


clean up topo/ folder


DEM2TOPO_RA.CSH - START
USER SHOULD PROVIDE DEM FILE
Working over 0/24864/0/12196 ...
 range decimation is:  2
blockmedian [INFORMATION]: Provides 3, expects 3-column binary data
blockmedian [INFORMATION]: Processing input table data
blockmedian [INFORMATION]: W: 0 E: 24864 S: 0 N: 12196 n_columns: 12432 n_rows: 6098
blockmedian [INFORMATION]: Input 3 columns via binary records using format ddd
blockmedian [INFORMATION]: Output 3 columns via binary records using format ddd
blockmedian [INFORMATION]: Reading Data Table from Standard Input stream
blockmedian [INFORMATION]: Writing Data Table to Standard Output stream
blockmedian [INFORMATION]: Calculating block medians
blockmedian [INFORMATION]: N read: 1975446 N used: 1967399 outside_area: 8047 N cells filled: 1967314
surface [INFORMATION]: Provides 3, expects 3-column binary data
surface [INFORMATION]: Internally speed up convergence by using the larger region -R-369/25231/-47/12241 (go from 12432 x 6098 to optimal 12800 x 6144, with speedup-factor 562.46335)
surface [INFORMATION]: Grid domain: W: 0 E: 24864 S: 0 N: 12196 n_columns: 12800 n_rows: 6144 [pixel registration]
surface [INFORMATION]: Processing input table data
surface [INFORMATION]: Input 3 columns via binary records using format ddd
surface [INFORMATION]: Reading Data Table from file temp.rat
surface [INFORMATION]: Minimum value of your dataset x,y,z at: 19131.859375 5645.1953125 -401.33215332
surface [INFORMATION]: Maximum value of your dataset x,y,z at: 2984.73950195 9421.07128906 2991.69628906
surface [INFORMATION]: Eliminate data points that are not nearest a node.
surface [WARNING]: 96 unusable points were supplied; these will be ignored.
surface [WARNING]: You should have pre-processed the data with block-mean, -median, or -mode.
surface [WARNING]: Check that previous processing steps write results with enough decimals.
surface [WARNING]: Possibly some data were half-way between nodes and subject to IEEE 754 rounding.
surface [INFORMATION]: Plane fit z = 983.72 + (-0.0998952 * col) + (0.0559746 * row)
surface [INFORMATION]: Normalize detrended data constraints by z rms = 457.991
surface [INFORMATION]: Select default convergence limit of 0.0457991 (100 ppm of L2 scale)
surface [INFORMATION]: Recompute data index for next iteration [stride = 512]
surface [INFORMATION]: ------------------------------------------
surface [INFORMATION]: Memory for data array          :   45.0 Mb
surface [INFORMATION]: Memory for final grid          :  300.4 Mb
surface [INFORMATION]: Memory for Briggs coefficients :   45.0 Mb
surface [INFORMATION]: Memory for node status         :   75.1 Mb
surface [INFORMATION]: ------------------------------------------
surface [INFORMATION]: Total memory use               :  465.5 Mb
surface [INFORMATION]: ==========================================
surface [INFORMATION]: Grid     Mode    Iteration       Max Change      Conv Limit      Total Iterations
surface [INFORMATION]: Set finite-difference coefficients [stride = 512]
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 512]
surface [INFORMATION]:  512     D             18        5.66433657588e-05       8.94512741773e-05            18
surface [INFORMATION]: Recompute data index for next iteration [stride = 256]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 512 to 256
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 256]
surface [INFORMATION]:  256     I             37        0.00013409949658        0.000178902548355            55
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 256]
surface [INFORMATION]:  256     D             15        0.00011529542706        0.000178902548355            70
surface [INFORMATION]: Recompute data index for next iteration [stride = 128]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 256 to 128
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 128]
surface [INFORMATION]:  128     I             37        0.000229306245205       0.000357805096709           107
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 128]
surface [INFORMATION]:  128     D             17        0.000280224182336       0.000357805096709           124
surface [INFORMATION]: Recompute data index for next iteration [stride = 64]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 128 to 64
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 64]
surface [INFORMATION]:   64     I             34        0.000663824962261       0.000715610193418           158
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 64]
surface [INFORMATION]:   64     D             22        0.00048732769659        0.000715610193418           180
surface [INFORMATION]: Recompute data index for next iteration [stride = 32]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 64 to 32
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 32]
surface [INFORMATION]:   32     I             32        0.00107186130112        0.00143122038684            212
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 32]
surface [INFORMATION]:   32     D           2699        0.00142984075164        0.00143122038684           2911
surface [INFORMATION]: Recompute data index for next iteration [stride = 16]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 32 to 16
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 16]
surface [INFORMATION]:   16     I             29        0.00249744410151        0.00286244077367           2940
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 16]
surface [INFORMATION]:   16     D           8838        0.00286178451508        0.00286244077367          11778
surface [INFORMATION]: Recompute data index for next iteration [stride = 8]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 16 to 8
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 8]
surface [INFORMATION]:    8     I             26        0.00416489929497        0.00572488154734          11804
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 8]
surface [INFORMATION]:    8     D           2806        0.00572121044336        0.00572488154734          14610
surface [INFORMATION]: Recompute data index for next iteration [stride = 4]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 8 to 4
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 4]
surface [INFORMATION]:    4     I             22        0.0094538976811 0.0114497630947      14632
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 4]
surface [INFORMATION]:    4     D           1477        0.0114346757645 0.0114497630947      16109
surface [INFORMATION]: Recompute data index for next iteration [stride = 2]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 4 to 2
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 2]
surface [INFORMATION]:    2     I             18        0.018510507754  0.0228995261894      16127
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 2]
surface [INFORMATION]:    2     D           1319        0.0228940684162 0.0228995261894      17446
surface [INFORMATION]: Recompute data index for next iteration [stride = 1]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 2 to 1
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 1]
surface [INFORMATION]:    1     I             14        0.0301508633271 0.0457990523788      17460
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 1]
surface [INFORMATION]:    1     D            562        0.0456157417381 0.0457990523788      18022
surface [INFORMATION]: Compute rms misfit and curvature.
surface [INFORMATION]: Fit info: N data points  N nodes mean error      rms error       curvature
surface [INFORMATION]:   1967218        78662145        -2.05845045828e-07      0.00148275090611     14918.2385824
surface [INFORMATION]: Increase pad by 184 184 23 23
surface [INFORMATION]: Writing grid to file pixel.grd
grd2cpt [INFORMATION]: Reading CPT from File /usr/local/share/cpt/gmt/gray.cpt
grd2cpt [INFORMATION]: Processing input grid(s)
grd2cpt [INFORMATION]: netCDF grid topo_ra.grd has no default CPT.
grd2cpt [INFORMATION]: Reading grid from file topo_ra.grd
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for all edges: natural
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for left   edge: natural
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for right  edge: natural
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for bottom edge: natural
grd2cpt [INFORMATION]: gmt_grd_BC_set: Set boundary condition for top    edge: natural
grd2cpt [INFORMATION]: Mean and S.D. of data are 517.772691809 589.456792833
grd2cpt [INFORMATION]: z = -400.092926025 and CDF(z) = 0
grd2cpt [INFORMATION]: z = -237.646583867 and CDF(z) = 0.0981352212729
grd2cpt [INFORMATION]: z = 21.6733386868 and CDF(z) = 0.240587381654
grd2cpt [INFORMATION]: z = 208.661247428 and CDF(z) = 0.339385414931
grd2cpt [INFORMATION]: z = 368.435520921 and CDF(z) = 0.445671701622
grd2cpt [INFORMATION]: z = 517.772691809 and CDF(z) = 0.521307695052
grd2cpt [INFORMATION]: z = 667.109862697 and CDF(z) = 0.602207192463
grd2cpt [INFORMATION]: z = 826.88413619 and CDF(z) = 0.702253907729
grd2cpt [INFORMATION]: z = 1013.87204493 and CDF(z) = 0.805802704869
grd2cpt [INFORMATION]: z = 1273.19196749 and CDF(z) = 0.895447632569
grd2cpt [INFORMATION]: z = 2989.06298828 and CDF(z) = 1
grd2cpt [INFORMATION]: Write CPT to Stream Standard output stream
grdimage [INFORMATION]: GMT_Parse_Options: Interval-setting -B options were reordered to appear before axis and frame -B options to ensure proper parsing.
grdimage [INFORMATION]: GMT_Parse_Options: New option order: topo_ra.grd -JX7i -P -Ctopo_ra.cpt -V -K -Bxaf+lRange -B"yaf+lReversed Azimuth" -BWSen
grdimage [INFORMATION]: Read header from file topo_ra.grd
grdimage [INFORMATION]: netCDF grid topo_ra.grd has no default CPT.
grdimage [INFORMATION]: Linear projection implies y-axis distance exaggeration relative to the x-axis by a factor of 2.0387
grdimage [INFORMATION]: Auto-frame interval for x-axis (item 0): a5000f1000
grdimage [INFORMATION]: Auto-frame interval for y-axis (item 0): a2000f1000
grdimage [INFORMATION]: Map scale is 1.39843 km per cm or 1:139843.
grdimage [INFORMATION]: Allocate and read data from file topo_ra.grd
grdimage [INFORMATION]: Reading grid from file topo_ra.grd
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for all edges: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for left   edge: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for right  edge: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for bottom edge: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for top    edge: natural
grdimage [INFORMATION]: gmt_cpt_default: Use specific CPT: topo_ra.cpt
grdimage [INFORMATION]: Reading CPT from File topo_ra.cpt
grdimage [INFORMATION]: Evaluate image pixel colors
grdimage [INFORMATION]: Basic z(x,y) -> gray image with no illumination.
grdimage [INFORMATION]: Plotting 8-bit grayshade image
PSL: DEFLATE compressed 75810336 to 10723139 bytes (85.9% savings at compression level 5)
Topo range/azimuth map: topo_ra.pdf
DEM2TOPO_RA.CSH - END
NO TOPO_RA SHIFT

INTF.CSH, FILTER.CSH - START
using command line
......master LED file S1_20150526_014937_F3.LED
.........aligned LED file S1_20150607_014937_F3.LED
using command line
......master LED file S1_20150526_014937_F3.LED
.........aligned LED file S1_20150526_014937_F3.LED
intf.csh
running phasediff...
reading topo topo_ra.grd
 xdim 24864, ydim 12196
filter.csh
setting range_dec = 8, azimuth_dec = 2
gauss_200 2 4 (1 2)
making amplitudes...
filtering interferogram...
making amplitude...
making correlation...
making phase...
filtering phase...
INTF.CSH, FILTER.CSH - END

SKIP UNWRAP PHASE

SKIP GEOCODE


Merging START
Number of Files to be merged is 3
Number of Files to be merged is 3
Number of Files to be merged is 3
Merging END

Recomputing the projection LUT...

MAKE LANDMASK -- START
REQUIRE FULL RESOLUTION COASTLINE FROM GMT

grdlandmask [NOTICE]: Downloading binned_GSHHS_f.nc for the first time - be patient
grdlandmask [INFORMATION]:   -> Download cache file: binned_GSHHS_f
grdlandmask [INFORMATION]: Downloading file http://oceania.generic-mapping-tools.org/geography/gshhg/binned_GSHHS_f.nc ...
grdlandmask [ERROR]: Libcurl Error: Timeout was reached
grdlandmask [ERROR]: Unable to obtain remote file binned_GSHHS_f.nc
grdlandmask [WARNING]: GSHHG version 2.2.0 or newer is needed to use coastlines with GMT.
        Get and install GSHHG from ftp://ftp.soest.hawaii.edu/gshhg/.
grdlandmask [ERROR]: Could not find file [GSHHG full resolution shorelines]
grd2xyz [ERROR]: Cannot find file landmask.grd
grd2xyz [ERROR]: Cannot find file landmask.grd
grd2xyz [ERROR]: File landmask.grd not found
[Session gmt (0)]: Error returned from GMT API: GMT_FILE_NOT_FOUND (16)
gmtinfo [ERROR]: No input data found!
surface [ERROR]: Must specify -R option
surface [INFORMATION]: Provides 3, expects 3-column binary data
gmtinfo [ERROR]: No input data found!
surface [ERROR]: Must specify -R option
surface [INFORMATION]: Provides 3, expects 3-column binary data
grdtrack [ERROR]: Cannot find file llr.grd
grdtrack [ERROR]: Must specify -G at least once
grdtrack [ERROR]: Cannot find file lla.grd
grdtrack [ERROR]: Must specify -G at least once
gmtconvert [WARNING]: File llpra is empty!
gmtconvert [WARNING]: No data records provided
gmtinfo [ERROR]: No input data found!
xyz2grd [ERROR]: Must specify -R option
grdsample [ERROR]: Cannot find file landmask_ra.grd
mv: cannot stat 'tmp.grd': No such file or directory
grd2xyz [ERROR]: Cannot find file landmask_ra.grd
grd2xyz [ERROR]: Cannot find file landmask_ra.grd
grd2xyz [ERROR]: File landmask_ra.grd not found
[Session gmt (0)]: Error returned from GMT API: GMT_FILE_NOT_FOUND (16)
grdinfo [ERROR]: Cannot find file landmask_ra.grd
grdinfo [ERROR]: Must specify one or more input files
xyz2grd [ERROR]: Option -I: Must specify positive increment(s)
mv: cannot stat 'tmp.grd': No such file or directory
rm: cannot remove 'landmask.grd': No such file or directory
MAKE LANDMASK -- END

SNAPHU.CSH - START
threshold_snaphu: 0.1
unwrapping phase with snaphu - higher threshold for faster unwrapping

snaphu v2.0.4
32 parameters input from file /usr/local/GMTSAR/share/gmtsar/snaphu/config/snaphu.conf.brief (297 lines total)
Reading wrapped phase from file phase.in
No weight file specified.  Assuming uniform weights
Reading correlation data from file corr.in
Calculating smooth-solution cost parameters
Building range cost arrays
Building azimuth cost arrays
Killed
xyz2grd [ERROR]: Cannot find file unwrap.out
xyz2grd [ERROR]: File unwrap.out not found
[Session gmt (0)]: Error returned from GMT API: GMT_FILE_NOT_FOUND (16)
xyz2grd [ERROR]: Cannot find file conncomp.out
xyz2grd [ERROR]: File conncomp.out not found
[Session gmt (0)]: Error returned from GMT API: GMT_FILE_NOT_FOUND (16)
grdmath [ERROR]: tmp.grd is not a number, operator or file name
mv: cannot stat 'tmp.grd': No such file or directory
grdgradient [ERROR]: Cannot find file unwrap.grd
grdinfo [ERROR]: Cannot find file unwrap.grd
grdinfo [ERROR]: Must specify one or more input files
makecpt [ERROR]: Option T: Must specify valid min[/max[/inc[<unit>|+n]]] option
grdimage [ERROR]: Cannot find file unwrap.grd
grdimage [ERROR]: Option -I: Must specify intensity file, value, or modifiers
psscale [NOTICE]: Downloading dcw-countries.txt for the first time - be patient
psscale [ERROR]: Libcurl Error: Timeout was reached
psscale [ERROR]: Unable to obtain remote file dcw-countries.txt
psscale [ERROR]: Color palette table unwrap.cpt is empty
[Session gmt (0)]: Error returned from GMT API: GMT_CPT_READ_ERROR (8)
[Session gmt (0)]: Error returned from GMT API: GMT_CPT_READ_ERROR (8)
psconvert [ERROR]: The file unwrap.ps has no BoundingBox in the first 20 lines or last 256 bytes. Use -A option.
Unwrapped phase map: unwrap.pdf
SNAPHU.CSH - END

GEOCODE-START
proj_ra2ll.csh
surface [INFORMATION]: Provides 5, expects 3-column binary data
surface [INFORMATION]: Internally speed up convergence by using the larger region -R-672/68448/-320/13504 (go from 4223 x 411 to optimal 4320 x 432, with speedup-factor 1470.5796)
surface [INFORMATION]: Grid domain: W: 96 E: 67664 S: 0 N: 13152 n_columns: 4320 n_rows: 432 [gridline registration]
surface [INFORMATION]: Processing input table data
surface [INFORMATION]: Input 5 columns via binary records using format ddddd
surface [INFORMATION]: Reading Data Table from file trans.dat
surface [INFORMATION]: Minimum value of your dataset x,y,z at: 3882.15771484 13151.2568359 -118.699996948
surface [INFORMATION]: Maximum value of your dataset x,y,z at: 68452.8828125 -5.51726484299 -115.835830688
surface [INFORMATION]: Eliminate data points that are not nearest a node.
surface [WARNING]: 4689743 unusable points were supplied; these will be ignored.
surface [WARNING]: You should have pre-processed the data with block-mean, -median, or -mode.
surface [WARNING]: Check that previous processing steps write results with enough decimals.
surface [WARNING]: Possibly some data were half-way between nodes and subject to IEEE 754 rounding.
surface [INFORMATION]: Plane fit z = -118.461 + (0.000627252 * col) + (-0.000817927 * row)
surface [INFORMATION]: Normalize detrended data constraints by z rms = 0.0328612
surface [INFORMATION]: Select default convergence limit of 3.28612e-06 (100 ppm of L2 scale)
surface [INFORMATION]: Recompute data index for next iteration [stride = 144]
surface [INFORMATION]: ------------------------------------------
surface [INFORMATION]: Memory for data array          :   39.4 Mb
surface [INFORMATION]: Memory for final grid          :    7.2 Mb
surface [INFORMATION]: Memory for Briggs coefficients :   39.4 Mb
surface [INFORMATION]: Memory for node status         :    1.8 Mb
surface [INFORMATION]: ------------------------------------------
surface [INFORMATION]: Total memory use               :   87.8 Mb
surface [INFORMATION]: ==========================================
surface [INFORMATION]: Grid     Mode    Iteration       Max Change      Conv Limit      Total Iterations
surface [INFORMATION]: Set finite-difference coefficients [stride = 144]
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 144]
surface [INFORMATION]:  144     D             31        1.91950576348e-08       2.28202684013e-08            31
surface [INFORMATION]: Recompute data index for next iteration [stride = 48]
surface [INFORMATION]: Expand grid by factor of 3 when going from stride = 144 to 48
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 48]
surface [INFORMATION]:   48     I             33        6.45548068528e-08       6.84608052039e-08            64
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 48]
surface [INFORMATION]:   48     D             24        4.93587195489e-08       6.84608052039e-08            88
surface [INFORMATION]: Recompute data index for next iteration [stride = 16]
surface [INFORMATION]: Expand grid by factor of 3 when going from stride = 48 to 16
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 16]
surface [INFORMATION]:   16     I             33        1.19169316001e-07       2.05382415612e-07           121
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 16]
surface [INFORMATION]:   16     D             23        1.64072040087e-07       2.05382415612e-07           144
surface [INFORMATION]: Recompute data index for next iteration [stride = 8]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 16 to 8
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 8]
surface [INFORMATION]:    8     I             22        3.29172386777e-07       4.10764831223e-07           166
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 8]
surface [INFORMATION]:    8     D            379        4.09951587552e-07       4.10764831223e-07           545
surface [INFORMATION]: Recompute data index for next iteration [stride = 4]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 8 to 4
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 4]
surface [INFORMATION]:    4     I             20        5.69681888399e-07       8.21529662447e-07           565
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 4]
surface [INFORMATION]:    4     D           1367        8.18989124767e-07       8.21529662447e-07          1932
surface [INFORMATION]: Recompute data index for next iteration [stride = 2]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 4 to 2
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 2]
surface [INFORMATION]:    2     I             17        1.11148524074e-06       1.64305932489e-06          1949
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 2]
surface [INFORMATION]:    2     D            214        1.61806909005e-06       1.64305932489e-06          2163
surface [INFORMATION]: Recompute data index for next iteration [stride = 1]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 2 to 1
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 1]
surface [INFORMATION]:    1     I             14        2.53306206694e-06       3.28611864979e-06          2177
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 1]
surface [INFORMATION]:    1     D            478        3.27275732274e-06       3.28611864979e-06          2655
surface [INFORMATION]: Compute rms misfit and curvature.
surface [INFORMATION]: Fit info: N data points  N nodes mean error      rms error       curvature
surface [INFORMATION]:   1721442         1870993        8.90435322945e-06       0.00192323597102     1033.18834107
surface [INFORMATION]: Increase pad by 48 49 10 11
surface [INFORMATION]: Writing grid to file raln.grd
surface [INFORMATION]: Provides 5, expects 3-column binary data
surface [INFORMATION]: Internally speed up convergence by using the larger region -R-672/68448/-320/13504 (go from 4223 x 411 to optimal 4320 x 432, with speedup-factor 1470.5796)
surface [INFORMATION]: Grid domain: W: 96 E: 67664 S: 0 N: 13152 n_columns: 4320 n_rows: 432 [gridline registration]
surface [INFORMATION]: Processing input table data
surface [INFORMATION]: Input 5 columns via binary records using format ddddd
surface [INFORMATION]: Reading Data Table from file trans.dat
surface [INFORMATION]: Minimum value of your dataset x,y,z at: -8.17806243896 672.183288574 32.5999984741
surface [INFORMATION]: Maximum value of your dataset x,y,z at: 68437.4375 13151.7285156 34.5483322144
surface [INFORMATION]: Eliminate data points that are not nearest a node.
surface [WARNING]: 4689743 unusable points were supplied; these will be ignored.
surface [WARNING]: You should have pre-processed the data with block-mean, -median, or -mode.
surface [WARNING]: Check that previous processing steps write results with enough decimals.
surface [WARNING]: Possibly some data were half-way between nodes and subject to IEEE 754 rounding.
surface [INFORMATION]: Plane fit z = 32.4924 + (9.32563e-05 * col) + (0.00396395 * row)
surface [INFORMATION]: Normalize detrended data constraints by z rms = 0.00710597
surface [INFORMATION]: Select default convergence limit of 7.10597e-07 (100 ppm of L2 scale)
surface [INFORMATION]: Recompute data index for next iteration [stride = 144]
surface [INFORMATION]: ------------------------------------------
surface [INFORMATION]: Memory for data array          :   39.4 Mb
surface [INFORMATION]: Memory for final grid          :    7.2 Mb
surface [INFORMATION]: Memory for Briggs coefficients :   39.4 Mb
surface [INFORMATION]: Memory for node status         :    1.8 Mb
surface [INFORMATION]: ------------------------------------------
surface [INFORMATION]: Total memory use               :   87.8 Mb
surface [INFORMATION]: ==========================================
surface [INFORMATION]: Grid     Mode    Iteration       Max Change      Conv Limit      Total Iterations
surface [INFORMATION]: Set finite-difference coefficients [stride = 144]
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 144]
surface [INFORMATION]:  144     D             31        4.00253911937e-09       4.93470482657e-09            31
surface [INFORMATION]: Recompute data index for next iteration [stride = 48]
surface [INFORMATION]: Expand grid by factor of 3 when going from stride = 144 to 48
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 48]
surface [INFORMATION]:   48     I             35        1.21435060189e-08       1.48041144797e-08            66
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 48]
surface [INFORMATION]:   48     D             24        9.48750012685e-09       1.48041144797e-08            90
surface [INFORMATION]: Recompute data index for next iteration [stride = 16]
surface [INFORMATION]: Expand grid by factor of 3 when going from stride = 48 to 16
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 16]
surface [INFORMATION]:   16     I             33        3.68875981405e-08       4.44123434391e-08           123
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 16]
surface [INFORMATION]:   16     D             27        3.52816410861e-08       4.44123434391e-08           150
surface [INFORMATION]: Recompute data index for next iteration [stride = 8]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 16 to 8
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 8]
surface [INFORMATION]:    8     I             24        5.68755866843e-08       8.88246868782e-08           174
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 8]
surface [INFORMATION]:    8     D            392        8.65734386338e-08       8.88246868782e-08           566
surface [INFORMATION]: Recompute data index for next iteration [stride = 4]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 8 to 4
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 4]
surface [INFORMATION]:    4     I             21        1.37828175634e-07       1.77649373756e-07           587
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 4]
surface [INFORMATION]:    4     D           1268        1.7680351794e-07        1.77649373756e-07          1855
surface [INFORMATION]: Recompute data index for next iteration [stride = 2]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 4 to 2
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 2]
surface [INFORMATION]:    2     I             16        3.42488871676e-07       3.55298747513e-07          1871
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 2]
surface [INFORMATION]:    2     D            238        3.54990629653e-07       3.55298747513e-07          2109
surface [INFORMATION]: Recompute data index for next iteration [stride = 1]
surface [INFORMATION]: Expand grid by factor of 2 when going from stride = 2 to 1
surface [INFORMATION]: Fill in expanded grid by bilinear interpolation [stride = 1]
surface [INFORMATION]:    1     I             13        5.7004063247e-07        7.10597495026e-07          2122
surface [INFORMATION]: Determine nearest point and set Briggs coefficients [stride = 1]
surface [INFORMATION]:    1     D            465        7.09907138206e-07       7.10597495026e-07          2587
surface [INFORMATION]: Compute rms misfit and curvature.
surface [INFORMATION]: Fit info: N data points  N nodes mean error      rms error       curvature
surface [INFORMATION]:   1721442         1870993        5.04318706981e-06       0.00151859882844     741.22644896
surface [INFORMATION]: Increase pad by 48 49 10 11
surface [INFORMATION]: Writing grid to file ralt.grd
Killed
Sampling in geocoordinates with 50 meter pixels ...
gmtinfo [ERROR]: No input data found!
range: Subscript out of range.
gmtmath [ERROR]: Operation "DIV" requires 2 operands
gmtmath [ERROR]: Operation "MUL" requires 2 operands
gmtinfo [ERROR]: No input data found!
blockmedian [ERROR]: Unable to decode  as a floating point number
blockmedian [ERROR]: Option -I parsing failure.  Correct syntax:

  -I<xinc>[+e|n][/<yinc>[+e|n]]
     Specify increment(s) and optionally append units or modifiers. For geographic regions
     in degrees you can optionally append units from this list: (d)egree [Default],
     (m)inute, (s)econd, m(e)ter, (f)oot, (k)ilometer, (M)ile, (n)autical mile, s(u)rvey
     foot.
       +e Adjust the region to fit increments [Adjust increment to fit domain].
       +n Increment specifies the number of nodes instead. Then, the actual increments are
          calculated from the given domain and node-registration settings (see Appendix B
          for details).
     Note: If -R<grdfile> was used then -I (and -R and maybe -r) have been set; use -I to
     override those increments.
blockmedian [ERROR]: Must specify -R option
blockmedian [ERROR]: Option -I: Must specify positive increment(s)
blockmedian [INFORMATION]: Provides 3, expects 3-column binary data
xyz2grd [ERROR]: Unable to decode  as a floating point number
xyz2grd [ERROR]: Option -I parsing failure.  Correct syntax:

  -I<xinc>[+e|n][/<yinc>[+e|n]]
     Specify increment(s) and optionally append units or modifiers. For geographic regions
     in degrees you can optionally append units from this list: (d)egree [Default],
     (m)inute, (s)econd, m(e)ter, (f)oot, (k)ilometer, (M)ile, (n)autical mile, s(u)rvey
     foot.
       +e Adjust the region to fit increments [Adjust increment to fit domain].
       +n Increment specifies the number of nodes instead. Then, the actual increments are
          calculated from the given domain and node-registration settings (see Appendix B
          for details).
     Note: If -R<grdfile> was used then -I (and -R and maybe -r) have been set; use -I to
     override those increments.
xyz2grd [ERROR]: Must specify -R option
xyz2grd [ERROR]: Option -I: Must specify positive increment(s)
proj_ra2ll.csh
Sampling in geocoordinates with 50 meter pixels ...
blockmedian [INFORMATION]: Provides 3, expects 3-column binary data
blockmedian [INFORMATION]: Processing input table data
blockmedian [INFORMATION]: W: -118.844444444 E: -115.883333333 S: 32.5166666667 N: 34.5458333333 n_columns: 5330 n_rows: 4870
blockmedian [INFORMATION]: Input 3 columns via binary records using format fff
blockmedian [INFORMATION]: Output 3 columns via binary records using format fff
blockmedian [INFORMATION]: Reading Data Table from file llp
blockmedian [INFORMATION]: Writing Data Table to Standard Output stream
blockmedian [INFORMATION]: Calculating block medians
blockmedian [INFORMATION]: N read: 39229672 N used: 39229672 outside_area: 0 N cells filled: 13886491
proj_ra2ll.csh
Killed
Sampling in geocoordinates with 50 meter pixels ...
gmtinfo [ERROR]: No input data found!
range: Subscript out of range.
gmtmath [ERROR]: Operation "DIV" requires 2 operands
gmtmath [ERROR]: Operation "MUL" requires 2 operands
gmtinfo [ERROR]: No input data found!
blockmedian [ERROR]: Unable to decode  as a floating point number
blockmedian [ERROR]: Option -I parsing failure.  Correct syntax:

  -I<xinc>[+e|n][/<yinc>[+e|n]]
     Specify increment(s) and optionally append units or modifiers. For geographic regions
     in degrees you can optionally append units from this list: (d)egree [Default],
     (m)inute, (s)econd, m(e)ter, (f)oot, (k)ilometer, (M)ile, (n)autical mile, s(u)rvey
     foot.
       +e Adjust the region to fit increments [Adjust increment to fit domain].
       +n Increment specifies the number of nodes instead. Then, the actual increments are
          calculated from the given domain and node-registration settings (see Appendix B
          for details).
     Note: If -R<grdfile> was used then -I (and -R and maybe -r) have been set; use -I to
     override those increments.
blockmedian [ERROR]: Must specify -R option
blockmedian [ERROR]: Option -I: Must specify positive increment(s)
blockmedian [INFORMATION]: Provides 3, expects 3-column binary data
xyz2grd [ERROR]: Unable to decode  as a floating point number
xyz2grd [ERROR]: Option -I parsing failure.  Correct syntax:

  -I<xinc>[+e|n][/<yinc>[+e|n]]
     Specify increment(s) and optionally append units or modifiers. For geographic regions
     in degrees you can optionally append units from this list: (d)egree [Default],
     (m)inute, (s)econd, m(e)ter, (f)oot, (k)ilometer, (M)ile, (n)autical mile, s(u)rvey
     foot.
       +e Adjust the region to fit increments [Adjust increment to fit domain].
       +n Increment specifies the number of nodes instead. Then, the actual increments are
          calculated from the given domain and node-registration settings (see Appendix B
          for details).
     Note: If -R<grdfile> was used then -I (and -R and maybe -r) have been set; use -I to
     override those increments.
xyz2grd [ERROR]: Must specify -R option
xyz2grd [ERROR]: Option -I: Must specify positive increment(s)
grdinfo [ERROR]: Cannot find file phasefilt_ll.grd
grdinfo [ERROR]: Must specify one or more input files
gmtmath [ERROR]: Operation "INV" requires 1 operands
grdimage [ERROR]: Cannot find file phasefilt_ll.grd
Make phasefilt_ll.kml and phasefilt_ll.png
psconvert [ERROR]: Option -E: No argument provided
rm: No match.
grdimage [INFORMATION]: Read header from file phasefilt_mask_ll.grd
grdimage [INFORMATION]: netCDF grid phasefilt_mask_ll.grd has no default CPT.
grdimage [INFORMATION]: Round-off patrol changed grid limit for xmin from -118.8444444399853 to -118.8444444399853
grdimage [INFORMATION]: Round-off patrol changed grid limit for xmax from -115.8833333289853 to -115.8833333289853
grdimage [INFORMATION]: Round-off patrol changed grid limit for ymin from 32.51666666559846 to 32.51666666559846
grdimage [INFORMATION]: Round-off patrol changed grid limit for ymax from 34.54583333219846 to 34.54583333219846
grdimage [INFORMATION]: Map scale is 0.000393701 km per cm or 1:39.3701.
grdimage [INFORMATION]: Allocate and read data from file phasefilt_mask_ll.grd
grdimage [INFORMATION]: Reading grid from file phasefilt_mask_ll.grd
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for all edges: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for left   edge: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for right  edge: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for bottom edge: natural
grdimage [INFORMATION]: gmt_grd_BC_set: Set boundary condition for top    edge: natural
grdimage [INFORMATION]: gmt_cpt_default: Use specific CPT: phase.cpt
grdimage [INFORMATION]: Reading CPT from File phase.cpt
grdimage [INFORMATION]: Evaluate image pixel colors
grdimage [INFORMATION]: Basic z(x,y) -> color image with no illumination.
grdimage [INFORMATION]: Plotting 24-bit color image
PSL: Too many colors to make colormap - using 24-bit direct color instead.
PSL: DEFLATE compressed 77871300 to 21748383 bytes (72.1% savings at compression level 5)
Make phasefilt_mask_ll.kml and phasefilt_mask_ll.png
psconvert [INFORMATION]: Processing phasefilt_mask_ll.ps...
psconvert [INFORMATION]: Find HiResBoundingBox ...
psconvert [INFORMATION]: Figure dimensions: Width: 213.18 points [7.52052 cm]  Height: 146.1 points [5.15408 cm]
psconvert [INFORMATION]: [144 144 357.18 290.1]...
psconvert [INFORMATION]: Convert to PNG...
gs -q -dNOPAUSE -dBATCH -dNOSAFER -dSCANCONVERTERTYPE=2 -dMaxBitmap=2147483647 -dUseFastColor=true -dGraphicsAlphaBits=2 -dTextAlphaBits=4 -sDEVICE=pngalpha  -g5330x3653 -r1800 -sOutputFile='phasefilt_mask_ll.png' './psconvert_3755d.eps'
psconvert [INFORMATION]: Wrote KML file phasefilt_mask_ll.kml
grdinfo [ERROR]: Cannot find file corr_ll.grd
grdinfo [ERROR]: Must specify one or more input files
gmtmath [ERROR]: Operation "INV" requires 1 operands
grdimage [ERROR]: Cannot find file corr_ll.grd
Make corr_ll.kml and corr_ll.png
psconvert [ERROR]: Option -E: No argument provided
rm: No match.
GEOCODE END
rm: No match.
rajashree@Santanu:~/S1A_SLC_TOPS_LA$ ls -lh *.ps
ls: cannot access '*.ps': No such file or directory
rajashree@Santanu:~/S1A_SLC_TOPS_LA$ cd merge/
rajashree@Santanu:~/S1A_SLC_TOPS_LA/merge$ ls -lh *.ps
-rw-r--r-- 1 rajashree rajashree 0 Apr 20 03:09 corr_ll.ps
-rw-r--r-- 1 rajashree rajashree 0 Apr 20 03:08 phasefilt_ll.ps
-rw-r--r-- 1 rajashree rajashree 0 Apr 20 03:02 unwrap.ps
rajashree@Santanu:~/S1A_SLC_TOPS_LA/merge$ cd ..
rajashree@Santanu:~/S1A_SLC_TOPS_LA$ gmt psxy -R0/10/0/10 -Jx1i -T -K > test.ps
psxy [WARNING]: Your plot (WxH = 25.40 x 25.40 cm) placed at (2.54, 2.54 cm) may exceed your PS_MEDIA (WxH = 29.70 x 20.99 cm)
rajashree@Santanu:~/S1A_SLC_TOPS_LA$ ls -lh test.ps
-rw-r--r-- 1 rajashree rajashree 21K Apr 20 10:24 test.ps
rajashree@Santanu:~/S1A_SLC_TOPS_LA$
