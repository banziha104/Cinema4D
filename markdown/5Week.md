# 5

Floor : 끝없는 바닥
Background : 끝 없는 배경


Compositing Tag : 
    - Tag -> Compositing Background : 배경과 바닥을 붙임
    
# Light

- 라이트 시점으로 보기 : Light -> View에 Camera -> Set as Camera -> 작업 -> defalut camera

- GENARAL : 일반
    - Type 
        -   Omni : 한점에서 360도 발산
        -   Spot : 한점에 빛을 발산
        -   Infinite : 태양광의 원리와 비슷하며, light의 위치와 상관없이 발산
        -   Area : 면적에 따라 발산을하며, 면적이 커지면 빛의강도가 썌짐
    - Diffuse : Edge를 제외하고 맺히는 
    - Specular : Edge에 맺히는 상
    - GI  iLLumination : 켜놓으면됌
    - Visible : 빛이 보일수 있게함
        - Volumetric : 
- SHADOW : 그림자

- 3점 조명 : 
    -   Defalut Light : Omni, Area , 기본 라이트
    -   Fill light : 어두운 부분을 채워주는 라이트, 난색을씀
    -   Back light : c4d 특성상 floor를 뚫고 빛을 맺히는게 가능하기 때문에, 아래쪽에서 발산하는 , 2개 설치
    -   Top Light : 위쪽에서 발산하는 빛 , 어두운 부분을 커버
    -   Front light : 앞에서 보는빛
    -   Spectular : 엣지부분을 다듬음 (light -> general -> diffuse 끄고 )
    -   AO : Edge 부분을 어둡게 해줌


- Detail 
    - Falloff : 빛의 감소를 제어 : Inverse Square(Physically Accurate 설정)
    -

- Visible Light : 빛이 보이는 빛
    -   Falloff : 광원에서 멀면 약해짐
    -   Inner Distance : 언제부터 약해질건지

- Noise : Visable Light에서 
    - illumination
    - Visiblity 
    - both : 둘다
    - Constrast : 강도

# Camera

- 하이라키 줌(오른쪽 검은색) : 카메라 시점으류 볼 수 있음
- Object
    -   Projection : 카레라를 보는 방법을 택함
        -   Perspective 
        -   Parallel  
        -   isometric
- Pysical : Pysical 렌더시에 사용
- Detail
    -   Cliping : 자르기 설정
    - DOF map Front Blur : 실제 눈처 블러를 줌, Effect의 Depth of Field 를 줘야함
- Steroscopic 
- Compoistion : 그냥도와줄때씀
- cmd + shift + z : 카메라 뒤로가기 
- camera -> 우클릭 -> Protection Tag : 카메라 고정  

# Effect 

### Ambient Occlusion

- Maximum Ray Length : 아래부터 얼마만큼 적용할지
- Color : 색