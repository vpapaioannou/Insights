# Insights
Tutorials about various subjects I encountered as Computer Engineer.
These tutorials neither cover any subject in detail nor this is their purpose. The intention is to give a quick and to the point guidance or answer.

Table of Contents
<ul>
  <li><span><b>Linux - Administration</b></span>
    <ul>
      <li>
        <a href="https://askubuntu.com/questions/749176/no-space-left-on-device-even-after-deleting-files">No space left on device even after deleting files</a>
      </li>
      <li>
        <span><i>Swap space : when RAM memory is not enough</i></span>
        <ul>
          <li>
            <a href="https://help.ubuntu.com/community/SwapFaq#What_is_swappiness_and_how_do_I_change_it.3F">Ubuntu documentation</a>
          </li>
          <li>
            <a href="https://help.ubuntu.com/community/SwapFaq#What_is_swappiness_and_how_do_I_change_it.3F">Empty swap space to restore performance</a>
          </li>
        </ul>
      </li>
      <li><a href="https://unix.stackexchange.com/questions/80822/ubuntu-unity-attach-script-to-launcher">Create desktop application launch button for bash script</a>
      </li>
      <li><a href="https://askubuntu.com/questions/710609/how-to-run-multiple-commands-in-parallel-and-see-output-from-both">Run multiple commands in parallel and see output from both?</a></li>
    </ul>
  </li>
</ul>
<ul>
  <li><span><b>TPCH</b></span>
<ul>
<li>Creating dbgen script</li>
<li>Generating data</li>
<li>Loading data into PostgreSQL</li>
</ul>
</li>
<li><span><b>PostgreSQL</b></span>
<ul>
<li>Changing data default directory</li>
<li>Playing with tablespaces - Handling scalability issues</li>
<li>Playing with CSV files</li>
</ul>
</li>
  <li><span><b>Scale matters</b></span>
<ul>
<li>Disk usage commands <code>df</code>, <code>du</code></li>
<li>Command <code>mount</code></li>
<li>Loading data to <code>Hadoop</code> the right way</li>
<li>Redirecting <code>Hive</code> execution temporary files</li>
</ul>
</li>
  <li><span><b>Cluster matters</b></span>
<ul>
<li>Handling cluster at once with <code>pdsh</code></li>
</ul>
<li><span><b>Git (Hub)</b></span>
<ul>
<li>Quick guide</li>
<li>Setting username and password once</li>
<li>Merge commits</li>
<li><a href="https://stackoverflow.com/questions/4873976/how-to-commit-only-modified-and-not-new-or-deleted-files">Commit only modified files</a></li>
<li>Revert code changes</li>
  <li><a href="https://www.fizerkhan.com/blog/posts/clean-up-your-local-branches-after-merge-and-delete-in-github#:~:text=The%20command%20git%20remote%20prune,an%20option%20%2D%2Ddry%2Drun%20">Clean up after merge</a></li>
  <li><a href="https://stackoverflow.com/questions/28195778/git-stash-apply-with-interactive-mode">Interactive resolution of conflicts when `pull` w/ `stash`</a></li>
  <li><a href="https://stackoverflow.com/questions/7200614/how-to-merge-remote-master-to-local-branch">Merge remote master to local branch (answer by Joey Adams).</a>
  </li>
  <li><a href="https://itsyndicate.org/blog/how-to-use-git-force-pull-properly/">Resolve conflicts w/ forced git pull</a>
  </li>
  <li><a href="https://askubuntu.com/questions/730754/how-do-i-show-the-git-branch-with-colours-in-bash-prompt">Show Git branch in terminal (answer by nardele salomon)</a></li>
  <li><a href="https://theshravan.net/blog/update-the-local-list-of-remote-branches-in-the-git-repository/">Update local branches list</a></li>
</ul>
<li><span><b>Coding and Debugging</b></span>
  <ul>
    <li>SSH tunneling</li>
    <li>Squid server</li>
    <li>Remote display - X11</li>
    <li>Eclipse IDE</li>
    <li><a href="https://www.swift.org/documentation/api-design-guidelines/">API Design Guidelines</a></li>
    <li><a href="http://bada55.io/">CSS colors w/ a name</a></li>
  </ul>
</li>
<li><span><b>Hadoop</b></span>
<ul>
<li>Debugging - Local logs</li>
</ul>
<li><span><b>Spark</b></span>
<ul>
<li>Spark submit</li>
<li>Spark shell</li>
<li>Playing with CSV files</li>
</ul>
</li>
<li><span><b>Hive</b></span>
<ul>
<li>Introduction</li>
<li>Installation</li>
<li>Executing queries</li>
<li>Playing with CSV files</li>
</ul>
  <li><span><b>Python</b></span>
    <ul>
      <li><a href="https://www.journaldev.com/15791/python-assert">Assertions (w/ variables)</a></li>
      <li><a href="https://realpython.com/python-logging/">Logging</a></li>
      <li><a href="https://stackoverflow.com/questions/19875789/django-gives-bad-request-400-when-debug-false">Logging in Django (answer by Yuseferi)</a></li>
      <li><a href="https://stackoverflow.com/questions/49433936/how-to-initialize-weights-in-pytorch">Pytorch Weight Initialization</a></li>
      <li><a href="https://stackoverflow.com/questions/49433936/how-to-initialize-weights-in-pytorch](https://intoli.com/blog/neural-network-initialization/">Understanding Neural Network Weight Initialization</a></li>
      <li><a href="https://stackoverflow.com/questions/49433936/how-to-initialize-weights-in-pytorch](https://intoli.com/blog/pca-and-svd/">How Are Principal Component Analysis and Singular Value Decomposition Related?</a></li>
      <li><a href="https://datascience.stackexchange.com/questions/5706/what-is-the-dying-relu-problem-in-neural-networks">What is the "dying ReLU" problem in neural networks?</a></li>
      <li><a href="https://github.com/wkentaro/labelme">Image labeling</a></li>
      <li><a href="https://www.machinelearninguru.com/deep_learning/data_preparation/hdf5/hdf5.html">PyTables</a></li>
      <li><a href="https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.axes.Axes.tick_params.html">Matplolib colorbar label size</a></li>
      <li><a href="https://stackoverflow.com/questions/26545051/is-there-a-way-to-delete-created-variables-functions-etc-from-the-memory-of-th">Delete created variables, functions, etc from the memory of the interpreter to avoid running out of memory while running code.</a></li>
      <li>3D-Models w/ VTK and more
        <ul>
          <li><a href="https://pyscience.wordpress.com/">PyScience - VTK</a></li>
          <li><a href="https://hengloose.medium.com/a-comprehensive-starter-guide-to-visualizing-and-analyzing-dicom-images-in-python-7a8430fcb7ed">A Comprehensive Guide To Visualizing and Analyzing DICOM Images in Python</a></li>
          <li><a href="https://www.datacamp.com/community/tutorials/matplotlib-3d-volumetric-data">Viewing 3D Volumetric Data With Matplotlib</a></li>
        </ul>
      </li>
      <li><a href="https://github.com/vinta/awesome-python">Awesome Python</a></li>
      <li><a href="https://github.com/kelvins/awesome-mlops">Awesome MLOPs</a></li>
      <li>OCR
        <ul>
          <li><a href="https://github.com/madmaze/pytesseract">PyTesseract</a></li>
          <li><a href="https://pyimagesearch.com/2021/11/15/tesseract-page-segmentation-modes-psms-explained-how-to-improve-your-ocr-accuracy/">Tesseract Page Segmentation Modes (PSMs) Explained: How to Improve Your OCR Accuracy</a></li>
          <li><a href="https://pyimagesearch.com/2021/09/20/language-translation-and-ocr-with-tesseract-and-python/">Language Translation and OCR with Tesseract and Python</a></li>
          <li><a href="https://pyimagesearch.com/2021/09/06/whitelisting-and-blacklisting-characters-with-tesseract-and-python/">Whitelisting and Blacklisting Characters with Tesseract and Python</a></li>
        </ul>
      </li>
    </ul>
  </li>
 <li><span><b>R</b></span>
  <ul>
    <li><a href="http://felixfan.github.io/ggplot2-remove-grid-background-margin/">ggplot2 Background</a></li>
    <li><a href="https://www.r-bloggers.com/t-tests/">Tests I</a></li>
    <li><a href="https://www.r-bloggers.com/add-p-values-and-significance-levels-to-ggplots/">Tests II</a></li>
    <li><a href="https://www.data-to-viz.com/caveat/boxplot.html">Boxplot and its pitfalls</a></li>
    <li><a href="https://stackoverflow.com/questions/60438297/r-histograms-with-shared-same-x-and-y-axes/60438728?noredirect=1#comment107179917_60438728">dynamic ggplot2 graphs (histograms) with same scale</a></li>
    <li><a href="https://linogaliana.netlify.app/post/datatable/datatable-nse/">Variable name in functions using rlang::sym</a></li>
    <li><a href="https://www.tidyverse.org/blog/2020/02/glue-strings-and-tidy-eval/">Variable name in functions using {{}}</a>
    </li>
</li>
  </ul>
 </li>
 <li><span><b>Markdown</b></span>
    <ul>
      <li><a href="https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet">CheatSheet</a></li>
    </ul>
 </li>
 <li><span><b>Machine Learning / Deep Learning</b></span>
    <ul>
      <li><a href="https://neptune.ai/blog/evaluation-metrics-binary-classification?utm_campaign=blog-evaluation-metrics-binary-classification&utm_content=blog&utm_medium=answer&utm_source=quora">24 Evaluation Metrics for Binary Classification (And When to Use Them)</a></li>
      <li><a href="https://www.quora.com/What-is-an-intuitive-explanation-of-F-score?share=1">What is an intuitive explanation of F-score?</a></li>
    </ul>
 </li>
 <li><span><b>Spatial patterns analysis</b></span>
  <ul>
    <li><a href="https://www.seas.upenn.edu/~ese502/">NOTEBOOK ON SPATIAL DATA ANALYSIS</a>
    </li>
    <li><a href="https://blog.valdosta.edu/andersonlab/2018/05/03/point-pattern-analysis-visualizing-and-testing-for-inhomogeneity-by-dr-anderson/">Testing for inhomogeneity</a>
    </li>
  </ul>
 </li>
 <li><span><b>SQL Server for Linux</b></span>
    <ul>
      <li><a href="https://blog.csdn.net/u011641865/article/details/72317824">dpkg: error processing package msodbcsql17 (--configure):
 package msodbcsql17 is not ready for configuration
 cannot configure (current status 'half-installed')</a>
      </li>
      <li><a href="https://dba.stackexchange.com/questions/174175/how-do-i-totally-remove-sql-server-2017-on-ubuntu">How do I totally remove SQL Server 2017 on Ubuntu?</a>
      </li>
    </ul>
 </li>
 <li><span><b>Visual Studio</b></span>
  <ul>
    <li><a href="https://www.roelpeters.be/change-venv-for-python-in-vs-code/">Set (Python) virtual environment.</a></li>
    <li><a href="https://code.visualstudio.com/docs/getstarted/tips-and-tricks#vscode">Tips and Tricks</a></li>
    <li><a href="https://stackoverflow.com/questions/58255016/class-has-no-objects-member/58255140#58255140">class has no 'objects' member</a></li>
  </ul>
 </li>
<li><span><b>Radiology</b></span>
  <ul>
    <li><a href="https://www.startradiology.com/the-basics/x-rayct-technique/">X-ray/CT technique</a></li>
  </ul>
</li>

<li><span><b>DICOM</b></span>
  <ul>
    <li><a href="https://dicom.innolitics.com/ciods/ct-image">DICOM Standard Browser</a></li>
    <li><a href="https://dicomiseasy.blogspot.com/">DICOM is easy blog</a>
      <ul>
        <li><a href="https://dicomiseasy.blogspot.com/2013/06/getting-oriented-using-image-plane.html">Getting oriented using image plane module</a></li>
      </ul>
    </li>
    <li><a href="https://github.com/rordenlab/dcm2niix">dcm2niix</a></li>
    <li><a href="https://github.com/rordenlab/dcm2niix/issues/232">dcm2niix: Gantry tilt error</a></li>
    <li><a href="https://www.paraview.org/">Paraview: viewing stl files</a></li>
    <li><a href="https://www.brainvoyager.com/bv/doc/UsersGuide/CoordsAndTransforms/CoordinateSystems.html">Coordinate systems explained I</a></li>
    <li><a href="https://www.slicer.org/wiki/Coordinate_systems">Coordinate systems explained II</a></li>
    <li><a href="https://aws.amazon.com/blogs/machine-learning/de-identify-medical-images-with-the-help-of-amazon-comprehend-medical-and-amazon-rekognition/">AWS De-identification</a></li>
    <li><a href="https://cloud.google.com/healthcare/docs/how-tos/dicom-deidentify">Google De-identification</a></li>
    <li><a href="https://towardsdatascience.com/a-matter-of-grayscale-understanding-dicom-windows-1b44344d92bd">Understanding DICOM window width and window center.</a></li>
  </ul>
</li>

<li><span><b>SimpleITK</b></span>
  <ul>
    <li><a href="https://simpleitk.readthedocs.io/en/next/Examples/DicomSeriesFromArray/Documentation.html">DICOM series from array</a></li>
    <l><a href="https://github.com/SimpleITK/SimpleITK/issues/346">SimpleITK does not save metadata.</a></li>
  </ul>
 </li>

<li><span><b>NIFTI</b></span>
  <ul>
    <li><a href="https://brainder.org/2012/09/23/the-nifti-file-format/">NIFTI-1 explained</a></li>
    <li><a href="https://brainder.org/2015/04/03/the-nifti-2-file-format/">NIFTI-2 explained</a></li>
    <li><a href="https://nifti.nimh.nih.gov/nifti-1/documentation/nifti1diagrams_v2.pdf">NIFTI-1 data format: page 2</a></li>
    <li><a href="http://www.itksnap.org/pmwiki/pmwiki.php">ITK-snap: viewing nifti files</a></li>
    <li><a href="http://www.itksnap.org/pmwiki/pmwiki.php%3Fn%3DDocumentation.TutorialSectionNewVersionTwo">ITK-snap beginners short tutorial</a></li>
  </ul>
</li>

<li>
  <span><b>NLP</b></span>
  <ul>
    <li>Tesseract
      <ul>
        <li><a href="https://medium.com/geekculture/tesseract-ocr-understanding-the-contents-of-documents-beyond-their-text-a98704b7c655">Tesseract OCR: Understanding the Contents of Documents, Beyond Their Text</a></li>
        <li><a href="https://nanonets.com/blog/ocr-with-tesseract/">How to OCR with Tesseract, OpenCV and Python</a></li>
        <li><a href="https://fazlurnu.com/2020/06/23/text-extraction-from-a-table-image-using-pytesseract-and-opencv/">Text Extraction from a Table Image, using PyTesseract and OpenCV</a></li>
        <li><a href="https://tesseract-ocr.github.io/tessdoc/ImproveQuality.html">Improving the quality of the output</a></li>
        <li><a href="https://tesseract-ocr.github.io/tessdoc/tess3/ControlParams.html">A list of useful control parameters and config files.</a></li>
        <li><a href="https://tesseract-ocr.github.io/tessdoc/">Tesseract User Manual</a></li>
        <li><a href="https://github.com/tesseract-ocr/tesseract/blob/main/doc/tesseract.1.asc#config-files-and-augmenting-with-user-data">Manual</a></li>
        <li><a href="https://tesseract-ocr.github.io/tessdoc/Command-Line-Usage.html">Command Line Usage</a></li>
        <li><a href="https://tesseract-ocr.github.io/tessdoc/tess3/FAQ-Old.html">Frequently Asked Questions</a></li>
      </ul>
    </li>
    <li>PyTesseract
      <ul>
        <li><a href="https://github.com/madmaze/pytesseract">Home page</a></li>
        <li><a href="https://github.com/madmaze/pytesseract/blob/master/pytesseract/pytesseract.py">Main code</a></li>
      </ul>
    </li>
  </ul>
<li>
  <span><b>Angular</b></span>
    <ul>
      <li><a href="https://hackernoon.com/the-mechanics-of-dom-updates-in-angular-3b2970d5c03d">Understand how Angular and similar frameworks work.</a></li>
      <li><a href="https://stackoverflow.com/questions/48216330/angular-5-formgroup-reset-doesnt-reset-validators">Reset form properly (answer by Abhinav)</a></li>
      <li><a href="https://material.io/resources/icons/?style=baseline">Angular Material Icons</a></li>
      <li><a href="https://blog.angular-university.io/tag/angular-core/">Angular Core Blog</a></li>
  </ul>
</li>

<li><span><b>Docker</b></span>
    <ul>
      <li><a href="https://download.docker.com/">All platforms Docker standalone .deb files. Useful for offline installation.</a></li>
      <li><a href="http://www.openwebit.com/c/how-to-debug-docker-images/">Debug docker image I.</a></li>
      <li><a href="https://medium.com/@betz.mark/ten-tips-for-debugging-docker-containers-cde4da841a1d">Debug docker image II.</li>
      <li><a href="https://stackoverflow.com/questions/51026315/how-to-solve-unicodedecodeerror-in-python-3-6/51027262#51027262">How to solve UnicodeDecodeError in Python 3.6? (answer by Daniel)</a></li>
      <li><a href="https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user">Run Docker as non-root user I (non secure)</a>
      </li>
      <li><a href="https://docs.docker.com/engine/security/rootless/">Run Docker as non-root user II</a></li>
      <li><a href="https://docs.docker.com/engine/security/rootless/">Run Docker as non-root user II</a></li>
      <li><a href="https://serverfault.com/questions/701248/downloading-docker-image-for-transfer-to-non-internet-connected-machine/718470#718470">Save and load Docker images as files (answer by Booba Skaya). Useful for offline Docker image import/export</a></li>
      <li><a href="https://stackoverflow.com/questions/23513045/how-to-check-if-a-process-is-running-inside-docker-container">How to check if a process is running inside docker container?</a></li>
      <li>Linux Offline Docker installation
        <ul>
          <li><a href="https://docs.docker.com/engine/install/ubuntu/#install-from-a-package">Download .deb files</a></li>
          <li><a href="https://gist.github.com/lamhoangtung/d19bb72a99639a762b6d935fbd080c7c">Download NVIDIA .deb files</a></li>
          <li><a href="https://docs.docker.com/engine/install/ubuntu/#uninstall-old-versions">Uninstall any old version. Use purge instead of remove.</a></li>
          <li><a href="https://github.com/moby/moby/issues/41792#issuecomment-750863884">Stop Docker socket before installing</a></li>
        </ul>
      </li>
      <li>Performance
        <ul>
          <li><a href="https://sysdig.com/blog/container-isolation-gone-wrong/">Container isolation gone wrong</a></li>
          <li><a href="https://sysdig.com/blog/monitoring-greedy-containers-part-1/">Monitoring greedy containers (Part 1)</a></li>
          <li><a href="https://medium.com/hackernoon/another-reason-why-your-docker-containers-may-be-slow-d37207dec27f">Another reason why your Docker containers may be slow</a></li>
          <li><a href="https://medium.com/homullus/beating-some-performance-into-docker-for-mac-f5d1e732032c">Beating some performance into Docker for Mac</a></li>
          <li><a href="https://jitsu.com/blog/multi-platform-docker-builds">How to build Docker Images for Apple Silicon (aka M1 Chip)</a></li>
          <li><a href="https://www.docker.com/blog/speed-boost-achievement-unlocked-on-docker-desktop-4-6-for-mac/">Speed boost achievement unlocked on Docker Desktop 4.6 for Mac</a></li>
        </ul>
      </li>
  </ul>
</li>

  <li><span><b>Django</b></span>
      <ul>
        <li><a href="https://stackoverflow.com/questions/43765732/how-to-trace-this-attributeerror-nonetype-object-has-no-attribute-is-relati">AttributeError: 'NoneType' object has no attribute 'is_relation' during makemigrations (answer by Felipe Ferri)</a></li>
        <li><a href="https://www.fullstackpython.com/wsgi-servers.html">What is WSGI: Web Server Gateway Interface?</a></li>
        <li><a href="https://build.vsupalov.com/gunicorn-and-nginx/">Gunicorn and Nginx in a nutshell.</a></li>
        <li>Logging
          <ul>
            <li><a href="https://mattsegal.dev/file-logging-django.html">Save Django logs in production</a></li>
            <li><a href="https://mattsegal.dev/django-gunicorn-nginx-logging.html">Manage logs w/ Nginx, Gunicorn and Django</a></li>
            <li><a href=https://mattsegal.dev/django-logging-papertrail.html">Log aggregation w/ Papertrail</a></li>
            <li><a href="https://scripting4ever.wordpress.com/2020/07/27/how-to-log-the-request-and-response-via-django-middleware/">Log requests and responses when run in production</a></li>
            <li><a href="https://pypi.org/project/django-request-logging/">django-request-logging</a></li>
          </ul>
        </li>
        <li><a href="https://medium.com/django-rest-framework/django-rest-framework-viewset-when-you-don-t-have-a-model-335a0490ba6f">ViewSets w/o model.</a></li>
        <li><a href="https://realpython.com/customize-django-admin-python/">Customize Django Admin Page</a></li>
        <li>Scheduling
          <ul>
            <li><a href="https://stackoverflow.com/questions/62525295/how-to-use-python-to-schedule-tasks-in-a-django-application">How to use python to schedule tasks in a Django application</a></li>
            <li><a href="https://apscheduler.readthedocs.io/en/stable/index.html">Advanced Python Scheduler</a></li>
            <li><a href="https://github.com/jcass77/django-apscheduler">django-apscheduler</a></li>
            <li><a href="https://github.com/CodeEnvironment/django-rest-framework-code/tree/master/weather">Example 1</a></li>
            <li><a href="https://github.com/bobby-didcoding/did_django_schedule_jobs">Example 2</a></li>
            <li><a href="https://stackoverflow.com/questions/37429726/overriding-appconfig-ready">Troubleshooting 1</a></li>
            <li><a href="https://stackoverflow.com/questions/59225246/how-to-use-django-appconfig-ready?noredirect=1&lq=1">Troubleshooting 2</a></li>
          </ul>
        </li>
    </ul>
  </li>

  <li><span><b>VirtualBox</b><span>
    <ul>
      <li><a href="https://download.virtualbox.org/virtualbox/6.1.28/">VirtualBox resources downloading page</a></li>
    </ul>
  </li>

  <li><span><b>OSBoxes</b></span>
    <ul>
      <li><a href="https://www.osboxes.org/">Virtual machines for different OSs</a></li>
    </ul>
  </li>
  <li><span><b>Training</b></span>
    <ul>
      <li><a href="https://training.prace-ri.eu/">PRACE Training Portal</a></li>
    </ul>
  </li>
  <li><span><b>Statistics</b></span>
    <ul>
      <li><a href="https://sites.google.com/site/davidsstatistics/davids-statistics/notched-box-plots">Notched Box Plots</a></li>
    </ul>
  </li>
  <li><span><b>Workplace</b></span>
    <ul>
    <li><a href="https://hbr.org/2018/10/how-men-get-penalized-for-straying-from-masculine-norms">How Men Get Penalized for Straying from Masculine Norms </a></li>
    <li><a href="https://www.hrdive.com/news/study-men-are-punished-for-not-being-masculine-enough-on-the-job/539200/">Study: Men are punished for not being masculine enough on the job </a></li>
    </ul>
  </li>
</ul>
