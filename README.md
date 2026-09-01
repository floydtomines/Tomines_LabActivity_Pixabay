# Tomines_LabActivity_Pixabay
# Pixabay API Activity

**Name:** Floyd Vincent Tomines  
**Course/Section:** ITCC 40-B  
**Activity:** Pixabay API Lab

---

## Overview

This activity demonstrates how to use the Pixabay REST API with CURL. Four different API requests were created using search terms, media types, categories, sorting options, and result limits.

---

# Challenge 1: Rocket Launch

### Parameters

| Parameter | Value |
|---|---|
| Search Term | Rocket Launch |
| Data Type | Video |
| Category | Science |
| Editor's Choice | Yes |
| Results Per Page | 3 |



Challenge 1
curl "https://pixabay.com/api/videos/?key=57360729-a6acfa25e5129f81d9af6539a&q=rocket+launch&category=science&editors_choice=true&per_page=3"
<img width="1890" height="410" alt="road forest" src="https://github.com/user-attachments/assets/6ada61f7-69bb-42b1-b4af-0db2ca24c121" />

Challenge 2
curl "https://pixabay.com/api/videos/?key=57360729-a6acfa25e5129f81d9af6539a&q=basketball&category=sports&order=latest&per_page=3"
<img width="1894" height="420" alt="forest" src="https://github.com/user-attachments/assets/76208025-f225-46e3-9b78-9646468a45de" />

Challenge 3
curl "https://pixabay.com/api/videos/?key=57360729-a6acfa25e5129f81d9af6539a&q=forest&category=background&editors_choice=true&order=latest&per_page=3"
<img width="1908" height="406" alt="basketball" src="https://github.com/user-attachments/assets/85a43151-5d9f-46a2-be3f-05941562dd5c" />

Challenge 4
curl "https://pixabay.com/api/?key=57360729-a6acfa25e5129f81d9af6539a&q=road+forest&image_type=photo&category=nature&editors_choice=true&per_page=3"
<img width="1914" height="489" alt="rocket launch" src="https://github.com/user-attachments/assets/8d230ccc-1784-44d8-b60b-f5c38e9c4a51" />

