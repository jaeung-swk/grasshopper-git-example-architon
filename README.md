# grasshopper git example architon

<hr>

https://github.com/jaeung-swk/grasshopper-git-example-architon/pull/1 의 1번 pr 에서 추가된 파일은 다음과 같습니다.

1. grasshopper/sample_main.gh - 메인 파일입니다. 전체 로직을 실행하는 기준으로, 다른 모듈들을 불러와 합쳐지는 곳 역할입니다.
2. grasshopper/gh_clusters/cluster_sample_1.ghcluster - 모듈 단위 개발 개념으로 클러스터를 사용하기 위해 로직이 분리된 그래스호퍼 클러스터 파일입니다.
3. src/file_sample.py - 모듈 단위 개발 개념으로 로직 코드를 관리하기 위해 분리된 파이썬 파일입니다.

<hr>

https://github.com/jaeung-swk/grasshopper-git-example-architon/pull/2 의 2번 pr 에서는 python 파일만 바뀌는 것으로, 
1. 모두가 공유해서 사용할 sample_main.gh 파일은 개인이 변경하지 않습니다.
2. python 파일만 변경되고, 그 변경이 본인 쪽에 반영되면 sample_main 에서도 결과에 반영됩니다.

<hr>

https://github.com/jaeung-swk/grasshopper-git-example-architon/pull/3 의 3번 pr에서는 ghcluster 파일만 바뀌는 것으로,
1. 모두가 공유해서 사용할 sample_main.gh 파일은 개인이 변경하지 않습니다.
2. ghcluster 파일만 변경되고, 그 변경이 본인 쪽에 반영되면 sample_main 에서도 결과에 반영됩니다.

<hr>

협업을 하기 위한 방안 중의 예시로, 각자가 변경할 파일을 명확히 구분하고 관리하는 기준을 만드는 예시로 봐주시면 감사하겠습니다.

특히 git 을 사용하는 경우, 바이너리 파일의 충돌은 코드 merge 를 기대하기 어렵기 때문에 3번 pr 같은 확실한 구분이 필요할 수 있습니다.

그래스호퍼에서의 협업 과정에서 이미 알고 계신 방법이나 더 나은 방법이 있다면 물론 그 방법으로 사용해주시면 좋을 것 같습니다.