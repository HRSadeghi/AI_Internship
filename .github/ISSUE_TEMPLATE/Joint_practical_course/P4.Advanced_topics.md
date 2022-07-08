---
name: Phase04-Advanced topics in NN and DL
about: techniques in DL
title: Phase04-Advanced topics in NN and DL
labels: ''
assignees: ''

---

- [ ] Section 0: Classification and overfitting
  
    تسک طبقه بندی ای را که در قسمت معرفی شبکه انجام دادید را در نظر بگیرید. تعداد کل عکسهای آموزش را در دیتاستی که استفاده کردید در نظر بگیرید. این بار به اندازه ۱/۵ دیتا را به طور رندوم جدا کنید و این دیتای جداشده را به عنوان دیتای آموزشی استفاده کنید. با آموزش این مدل، نشان دهید مدل روی این دیتای جدا شده overfit می شود و باید جلوی آن را بگیریم. سعی کنید حالا با رگولاریزیشن مدل را بهتر کنید. همچنین سعی کنید با استفاده از dropout و batch normalization و pooling و augmentation هم در آموزش جدید استفاده کنید و بهبود را مشاهده کنید.

    از این [لینک](https://www.section.io/engineering-education/dropout-regularization-to-handle-overfitting-in-deep-learning-models/) میتوانید برای کمک بیشتر استفاده بگیرید.

  
     `[تعداد عکسهای آموزشی، نتایج و توضیحات  و ساختار شبکه تان را اینجا بنویسید]`


- [ ] Section 2: Classification and Transfer learning
  - [ ] 
    دیتاست [fashion-Mnist](https://pytorch.org/vision/stable/generated/torchvision.datasets.FashionMNIST.html) را دانلود کنید یا از طریق خود pytorch به آنه دسترسی پیدا کنید. حالا به روش های زیر مدل را آموزش دهید:
      - [ ] با یک backbone جدید، مشابه آنچه در بخش intro to NN استفاده کردید، با head ای که به تعداد fashion-mnist کلاس دارد را از اول آموزش بدهید.
  
  
      - [ ] در این قسمت مدلی را که در بخش intro to nn بر روی داده ۶کلاسه آموزش داده بودید لود کنید و head کلاسیفیکیشن را برداشته و head جدیدی که به تعداد fashion-mnist کلاس دارد قرار دهید و در دو حالت ۱. آموزش کل شبکه ۲. آموزش head شبکه را finetune کنید.
    نتایج را مقایسه کنید.
  - 
     `[تعداد عکسهای آموزشی، نتایج و توضیحات  و ساختار شبکه تان را اینجا بنویسید]`

