How To Use Robin?
=================
Follow the steps and you will learn the whole process.

Go To Our Site
---------------
    1. Go to `http://hicrobin.online/ <http://hicrobin.online/>`_

.. note::
    Remember to use **http**. Our site does not support *https*.

Loop Caller Result
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
We believe you already have different loop caller result files. If you want to generate loop caller result, we provided comprehensive bash scripts in `https://github.com/OluwadareLab/Robin/tree/main/loop_caller_runner <https://github.com/OluwadareLab/Robin/tree/main/loop_caller_runner>`_ . You need to update the paths in these bash scripts. For more information on how to run individual loop callers and to learn about parameters, we recommand you to read the corresponding tool's manuscript. If you wish to use docker environment, we provided our prebuild and ready to go docker images in `https://hub.docker.com/repositories/hchowdhu <https://hub.docker.com/repositories/hchowdhu>`_ .   


Fill The Form
--------------
    1. Click on *SUBMIT A JOB* button.
        .. image:: ./_static/image/submit_a_job_btn.png
    2. Fill the form with a *Job Title* (e.g. Loop caller analysis) and *Description* (e.g. Benchmarking of loop caller tools).
        .. image:: ./_static/image/form.png

Upload Loop Caller Result
------------------------------
    1. Type your *Tool Name* (e.g. cLoops).
    2. Type your tools' *Category* (e.g. Clustering) name (if you have one).
    3. Type your Resolution (e.g. 5000 for 5KB, 250000 for 250KB) and upload the corresponding result file in `BEDPE <https://bedtools.readthedocs.io/en/latest/content/general-usage.html#bedpe-format>`_ (*Without Header*) like format -
        
        ====  ==  ==  ====  == == == == ========= ========= == ==
        chr1  10  20  chr5  50 60 a1 30 :math:`+` :math:`-` 0  1
        chr9  30  40  chr9  80 90 a2 10 :math:`+` :math:`-` 2  1  
        ====  ==  ==  ====  == == == == ========= ========= == ==

        See these example files: :icon:`fa-solid fa-download`:download:`cLoops.bedpe <./_static/files/cLoops_GM12878_5k.bedpe>`, :download:`Chromosight.bedpe <./_static/files/Chromosight_GM12878_5k.bedpe>`, :download:`HiCExplorer.bedpe <./_static/files/HiCExplorer_GM12878_5k.bedpe>`, :download:`SIP.bedpe <./_static/files/SIP_GM12878_5k.bedpe>`.
    4. Add additional resolution result file (if you have multiple resolution result file) by clicking *Add Additional Resolution* and repeat step 3.
    5. You must provide at least two tools results following the same procedures, step 1 - 4.
    6. Add additional tools files (if you have multiple tools result files) by clicking *Add New Tool Data* and repeat step 1 - 4.
        .. image:: ./_static/image/upload_loop_result.png

Upload Protein Reference File
---------------------------------
    1. Type your *Protein Name* (e.g. H3K27ac) and upload reference file.
        See this example file: :icon:`fa-solid fa-download`:download:`h3k27ac.bedpe <./_static/files/h3k27ac.bedpe>`
    2. Add additional protein reference file (if you have multiple protein reference file) by clicking *Add New Reference File* and repeat step 1.
        .. image:: ./_static/image/upload_protein_files.png
    
Enable/Disable HiGlass
----------------------------------------
    1. If you want to visualize in HiGlass (read `full document <https://higlass.io/>`_ for more understanding), tick HiGlass (default) or untick HiGlass if you do not want to use it.
        .. image:: ./_static/image/enable_higlass.png
    2. If you tick HiGlass, provide *Assembly Name* (e.g. hg19, hg38) and upload the file (chromosome size file).
        See this example file: :icon:`fa-solid fa-download`:download:`hg19.chrom.sizes <./_static/files/hg19.chrom.sizes>`

        .. image:: ./_static/image/upload_ass_file.png

Submit Your Job
------------------
    1. Submit your job by clicking *Upload And Submit*.
        .. image:: ./_static/image/upload_n_submit_btn.png

After Job Submission
--------------------------
    1. Wait for Robin job upload to be completed.
    2. Once it is completed, you will be redirected to the queue page.
    3. Make sure to click on the *Bookmark* button to be able to access the job results later.
    4. Explore your result within different tabs (Overlap, Regression, Protein e.g. H3K27ac, HiGlass, AI Assistant).
        .. image:: ./_static/image/queue.png

