# Computer Vision Augmented AI

## Overview

<p>This ia an Augmented AI computer vision project that utilizes a CLIP ViT model to find potential matches between input images and a reference image set, then presents those potential matches in a clean GUI for a side-by-side Human in the Loop (HITL) review.</p>
<p>This project includes two notebooks.  The first notebook scans images and uses a pretrained CLIP-ViT-B-32 model to create image embeddings, then it creates an 
FAISS (Facebook AI Similarity Search) HNSW (Hierarchical Navigable Small World) index.  It also creates numpy file that
contains the filepaths for the reference images.  The faiss hnsw index file and image filepaths file will be used in the 
next notebook.</p>
<p>The second notebook scans images and uses a pretrained CLIP-ViT-B-32 model to create image embeddings, compares them to the reference
embeddings index created in the 01-create-reference-embeddings.ipynb notebook, then loads the images into a clean GUI to enable
Human in the Loop (HITL) side-by-side image review.  This brings the Augmented AI project full circle.</p>

## Screenshot from the HITL side-by-side Image Review

<img width="661" height="573" alt="Screenshot 2026-01-30 152214" src="https://github.com/user-attachments/assets/ffaad2fb-26ef-40bb-8b05-117471d885a2" />
