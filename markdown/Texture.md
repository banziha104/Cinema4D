# Texture

- 빈공간 더블클릭 : 새 Material 생성
- Material 더블클릭 : Material editor
    - diffusion : 더럽히기
    - luminance : 반사
    - Transparency : 투명도
    - Environment : 
    - Refraction : 반사
    - Refraction 
        - Blurries 
        - add
            - Dufuse , Irawan 
            - Backman, CGX : 금속 재질, Backman 추천 
                - Backman : Layer1 -> Add 변경 -> 조절 : 재질느낌을줄수있음.
                - Layer Fresnel : 도체, 투과에 대한 굴절율
                - Layer Color : 투과되는 색상
                - Layer Mask : 
               
            - Ward : 고무재
           
    - Bump : 왜곡은 되지만, 본 형태는 그대로임. 빛을 표현할 수 없음
    - Normal : 왜곡은 되지만, 본 형태는 그대로임, 빝의 표현할 수 없음
    - Displacement : 외각을 변형시킴
        - Sub Polygon Displacement
    - Alpha : Transparency 와 다르게 특정부분을가림
    - Glow : 추천하지않음.. 빛나는것처럼 보임
    
- 쉐이더
    - 텍스쳐 editor + Create : 3d 쉐이더 (높이 값도 계산)
    - 머터리얼데이터 + 텍스쳐 :  2d 쉐이더
        - Surface : 표면을 잡음
        - Layer : 층을 만

- 재질간의 차이
    - diffusion, luminance, reflectance 
    - 메탈 : 반사에 따라 많은 차이가남. 
    = 고무 : 상아 맺힘
    - 종이
    
- 1  - Sky : 하늘을 만
    - 스플라인 -> ㄴ 자를 만 -> 우클릭 + Create Point -> B-spline -> 복사 -> Loft에 넣음
    
    
맵핑  : Tag -> Projection (투영방식) -> UVW Mapping -> 텍스쳐 모드
    - Seamless
    - Cubic
        - Lentgh U 
        - Titles U : 한번만 씀
        
머터리얼 에디터 -> Layer Color : 투영될 것들

에디터블 모드 -> 면선택 -> 텍스쳐 투척 -> 한부분만 들어가게됌.
        
    
2번째 아이콘 : 부분 렌더링

셀렉션를 만들기 : 원하는 부분 (면) 선택 + Create -> Create Selection (셀렉션이 만들어짐)

copy shader

우클릭 -> 슬라이드 : 포인트가 엣지에 모서리에 따라서 움직임

Compositing Tag + Seen by Camera : 카메라에선 안보이지만, 사물에 영향을 미침(반사같은 것)

flat 하게만들기 -> color -> copy shader -> alpha -> texture -> paste shader -> 어트리뷰트 tile 제거

팁 : plane 에 루미넌스 반사판만들기


