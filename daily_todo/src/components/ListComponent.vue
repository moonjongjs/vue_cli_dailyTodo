<template>
  <div id="list">
    <div class="gap">
        <ul>
            <li><div>스타벅스 애플리케이션 Android 5.0 미만 버전 서비스 지원종료 안내</div></li>    
            <li><div>스타벅스 홈페이지 windows XP 미만 서비스 지원 종료안내</div></li>    
            <li><div>스타벅스 앱 내 e-Coupon / Gift Shop의 e-Gift Item 수량 표기 미노출 안내</div></li>    
            <li><div>스타벅스 애플리케이션 Android 5.0 미만 버전 서비스 지원종료 안내</div></li>    
            <li><div>코로나 방역조치 강화에 따른 고객 안내(수도권 및 2단계 상향 지역에 한함)</div></li>    
            <li><div>스타벅스 홈페이지/애플리케이션 일부 서비스 종료 안내</div></li>    
            <li><div>스타벅스 앱 내 e-Coupon / Gift Shop의 e-Gift Item 수량 표기 미노출 안내</div></li>    
            <li><div>개인정보 처리방침 및 영상정보처리기기 운영관리 방침 개정안내</div></li>    
            <li><div>PFSS(프리미어 푸드 서비스 스토어) 일반 푸드 운영 안내</div></li>    
            <li><div>Summer 시즌 사이렌 오더 내 음료 기본 설정 및 카테고리 변경 안내</div></li>    
        </ul>    
    </div>      
  </div>
</template>

<script>
export default {

}
</script>


<style scoped>

    #list {width:100%;}
    #list .gap {padding:15px 20px;}
    #list .gap ul {width:100%;}
    #list .gap ul li {border-bottom:1px solid #f2f2f2;}
    #list .gap ul li div {font-size:14px;line-height:35px;overflow:hidden;white-space:nowrap;text-overflow:ellipsis;background:#fff;padding:0 5px 0 17px;position:relative;z-index:1;}
    #list .gap ul li div:before {content:'';display:block;position:absolute;top:50%;left:5px;width:2px;height:2px;background:#888;margin-top:-1px;z-index:2;}
    
</style>