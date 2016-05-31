# separate-korean
한국어 초성/중성/종성 분리기 (검색엔진 용)

Usage:  

s = Separater('선린인터넷고등학교')
>

s.chosung
>['ㅅ', 'ㄹ', 'ㅇ', 'ㅌ', 'ㄴ', 'ㄱ', 'ㄷ', 'ㅎ', 'ㄱ']

s.jungsung
>['ㅓ', 'ㅣ', 'ㅣ', 'ㅓ', 'ㅔ', 'ㅗ', 'ㅡ', 'ㅏ', 'ㅛ']

s.jongsung
>['ㄴ', 'ㄴ', 'ㄴ', ' ', 'ㅅ', ' ', 'ㅇ', 'ㄱ', ' ']

s.sep_all
>['ㅅ', 'ㅓ', 'ㄴ', 'ㄹ', 'ㅣ', 'ㄴ', 'ㅇ', 'ㅣ', 'ㄴ', 'ㅌ', 'ㅓ', 'ㄴ', 'ㅔ', 'ㅅ', 'ㄱ', 'ㅗ', 'ㄷ', 'ㅡ', 'ㅇ', 'ㅎ', 'ㅏ', 'ㄱ', 'ㄱ', 'ㅛ']