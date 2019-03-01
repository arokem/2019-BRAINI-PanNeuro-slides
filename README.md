# PanNeuro: leveraging a community-based approach for big data neuroscience

Ariel Rokem1, Joe Hamman2, Ryan Abernathey3, Adrienne Fairhall1

1. The University of Washington
2. National Center for Atmospheric Research
3. Columbia University

Like neuroscience, many other fields of science are also experiencing a deluge
of large, heterogeneous, and noisy data. While all this data is likely to
provide profound insights, researchers struggle to store, manage, analyze and
understand it. The Pangeo project, funded by NASA and NSF, has developed a
community-based approach to addressing these difficulties in the geosciences.
The Pangeo approach relies on the following components: (1) Cloud computing: One
of the main principles that apply in this era of large datasets is that
computations should be brought to the data, rather than transferring and making
multiple copies. Cloud computing services provide a centralized location where
both data storage and computation on the data can co-locate. (2) Docker and
Kubernetes: these open-source tools enable reliable deployment of computational
environments across multiple users and multiple nodes in a scalable
cloud-compute cluster. (3) The Python open source software eco-system, including
components for numerical computing (e.g., Numpy and Scipy), machine learning
(e.g., Scikit Learn and Tensorflow), and scalable computing (e.g., Xarray and
Dask) and (4) the Jupyterlab user interface: this interface includes the Jupyter
notebook, that provides a basis for verifiable/reproducible computations, as
well as additional tools to manage computations and monitor them. Leveraging the
already existing investments created through the Pangeo project, we have created
PanNeuro for big data neuroscience, and we have created an instance of PanNeuro
to support data sharing and computation within a U19-funded team science
collaboration focused on brain circuits supporting learning and memory in the
human and non-human primate brain. Researchers in the collaboration upload
preprocessed datasets into a shared object-store in the cloud, which is attached
to the PanNeuro compute cluster. The data is then made available through the
Jupyter interface in Python, allowing researchers to compute on this data in
Jupyter notebooks, and to share these notebooks with others in the
collaboration.
