# Waste Recycling Image Segmentation

μ λ¦¬ : https://www.notion.so/Calier-Team-da6c4805228345bc9bc52f17236e7a57

## π₯Ό μμ¨μ°κ΅¬ - CNN(Plastic Segmentation)

### π· Rebuilders
* AI-Challenge ([Ashbee Kim](https://github.com/AshbeeKim))
* Plastics Segmentation ([Park jeong yeol](https://github.com/qkrwjdduf159))


### π Guidelines
```
# μ°μ  μμμ μ§νν  ν΄λ μμ±
$ mkdir <feature name>
$ cd <feature name>

# λ°©λ² 1 : organizationμμ λ°λ‘ μμ
$ git init
    # λ§μ½ git initμ νμ λ, λ‘μ»¬ λΈλμΉ λͺμ΄ main, masterλΌλ©΄
    $ git branch --move main(or master) <feature branch name>
$ git remote add origin git@github.com:Proj-Caliber/Waste-Recycling-Image-Segmentation.git
    # λ§μ½ remote nameμ originμ΄ μλ λ€λ₯Έ λͺμΉ­μΌλ‘ νκ³  μΆλ€λ©΄
    $ git remote rename origin <new name>
$ git pull origin <remote branch name>
$ git push -u origin <remote branch name>
```
μ΄ν μ§νν μμμ commit νκ³  $ git push origin <remote branch name>

μμμ΄ μ λΆ λλλ©΄, develop λΈλμΉλ‘ pull request λ λ¦¬κΈ°
    
</br>

### π κΆμ₯ μλ² νκ²½

* **OS : ubuntu 18.04**
* **CUDA : 11.1.1**
* **Python : ^3.7.7**


### ποΈ κ΅¬μ‘°
```
.
βββ assets
β   βββ data
β   βββ ...
β   βββ mask
β   βββ weights
βββ models
β   βββ detection
β   βββ segmentation
β   βββ transformer
βββ docs
    βββ paper-review
    βββ papers
    βββ tutorials
```


### λ°μ΄ν° μ κ·Ό κ²½λ‘
* case2
```
# π§ plastics segmentation
./assets/data
βββ test
β   βββ annotations
β   β   βββ PE
β   β   βββ PET
β   β   βββ PP
β   β   βββ PS
β   βββ image
β       βββ PE
β       βββ PET
β       βββ PP
β       βββ PS
βββ train
    βββ annotation
    β   βββ PE
    β   βββ PET
    β   βββ PP
    β   βββ PS
    βββ image
        βββ PE
        βββ PET
        βββ PP
        βββ PS
```


### β¨ μ°Έκ³  λ¬Έν λ° Repo by Roles

* [YoungpyoRyu](https://github.com/Youngpyoryu)
  * [U-Net++](https://paperswithcode.com/paper/unet-a-nested-u-net-architecture-for-medical)
  * [Deep-Net](https://paperswithcode.com/paper/semantic-image-segmentation-with-deep)
* [Ashbee Kim](https://github.com/AshbeeKim)
  * [Mask-RCNN and U-net Ensembled](https://paperswithcode.com/paper/mask-rcnn-and-u-net-ensembled-for-nuclei)
* [Park jeong yeol](https://github.com/qkrwjdduf159)
  * [MMDetection](https://paperswithcode.com/paper/mmdetection-open-mmlab-detection-toolbox-and) [RepositoryποΈ](https://github.com/open-mmlab/mmdetection)
  * [UNet](https://paperswithcode.com/paper/u-net-convolutional-networks-for-biomedical)
* [Yonje Olivia Choi](https://github.com/oliviachchoi)
  * [Faster R-CNN](https://paperswithcode.com/paper/faster-r-cnn-towards-real-time-object)
  * [Mask R-CNN](https://paperswithcode.com/paper/mask-r-cnn)

ποΈ λͺ¨λΈ κ΅¬νμ μν΄ μ°Έκ³ ν λΌλ¬Έμλλ€.

π¬ μ΄λ¦μ ν΄λ¦­νλ©΄, κ°μμ νλ‘νμ νμΈν  μ μμ΅λλ€.

π¬ If you interested in us, click name to check our profiles.


---

## LICENSE

This work is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/), and the underlying source code used to format and display that content is licensed under the [MIT license](https://github.com/github/choosealicense.com/blob/gh-pages/LICENSE.md).

![CC BY-SA 4.0](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)

![]()
