# VCS란?

__Git__ 을 소개하기 전에 VCS를 가장 먼저 알아야한다고 생각되어 먼저 소개해드리겠습니다! VCS란 Version Control System의 약자입니다. 우리말로는 버전관리시스템. 우리는 프로그램을 만들때, 프로그램명_V1, V2, V3 등 처럼 뒤에다가 붙여 저장합니다. 우리가 이렇게 하는 것도 버전관리의 일종이라고 볼 수 있습니다. 파일을 수정하고 저장했다가, 나중에 뭐가 잘못된거나 하면 다시 이전버턴으로 돌아갈 수 있도록 하는 것이 바로 버전관리의 정의입니다. 

# VCS의 종류

VCS의 종류는 세가지입니다. 

1. __로컬버전관리__   
컴퓨터에서 디렉토리 만들고 그 안에서 파일명으로 버전별로 관리하는 단순하고 일반적인 형태의 VSC방식입니다. 잘못될 위험이 크고 체계적이지 못하다는 단점이 있습니다.

2. __중앙집중식 버전관리(CVCS)__   
서버에다가 관리하는 형태, 프로젝트가 있다면 그 프로젝트 수정한 것을 서버에 올리고 다른 사람도 수정해서 서버로 올리는 형태입니다. 로컬에서는 관리를 안하고 서버에서만 관리하기 때문에 서버가 다운되거나, 정보가 날라가거나, 수정 충돌 문제가 발생할 수 있다.

3. __분산버전관리시스템__   
서버에서 관리하고 로컬에서도 관리를 한다. 서버가 날라가도 로컬이 있으며 로컬이 날라가도 서버가 있어서 매우 안적적인 시스템이다. Git이 이 방식을 쓴다.