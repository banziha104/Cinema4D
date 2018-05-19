# Spline

> 곡선과 관련된 객체

- Sketch : 그냥 그림
- Spline Smooth : 곡선을 변형함
- Spline Arcs Tool : path를 원형으로만듬 

<br>

- 우클릭 -> Soft Interpolation : 직선을 곡선으로
- 우클릭 -> Hard Interpolation : 곡선을 직선으로
- 우클릭 -> Champer : 포인트를 곡선으로만들어
- 우클릭 -> Create Outline : 곽을 만듬
- 우클릭 -> Connect object delete : 모든 패스를 합치고 필요없는 것은 지움
- 우클릭 -> Split : 선택된 객체를 분리

<br>

- Pen -> Move -> Pen : 동일 스플라인에서 나눠서 그릴수있음

<br>


- Equal Target Direction
- Space : 이전 기능으로 돌아감
- Shift + 핸들 : 한 쪽 핸들만 컨트롤할 수 있음
- Cmd + Point : 포인트삭제
- Cmd + 곡선 : 새포인트를 만들수 있음.
- Cmd + 바깥 : 포인트를 추가로 이음
- Cmd + shift + 바깥 : 시작점으로 부터 포인트를 추가로 이음
- Cmd + A : 전체 포인트 선택

<br>

- Spline Substract 등등 -> pathfinder

<br>

- Type 
    - Bezier : 세밀한 곡류
    - Linear : 직각으로만듬
    - Cubic : Overshooting 을 이용해 자연스럽게 이음
    - B-Spline : 가장 부드럽게 만듬 *
    
<br>
- Attribute
    - Plane : 바라볼 방향
    - Ellipse : 타원으로만듬
    - Vertorizer : 이미지를 불러서 윤곽에따라 패스를만듬
        - c를 누르면 editable로만듬

    
