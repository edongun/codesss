# codesss


sk-rJ11111111111111111111111UYow8rKhOFdhcfzuYoT3BlbkF1111111111111111111111111J0mncELfuxSEczTCLFNNx
sk-Y62m9gPDf111111111111111111111UPPK0t3KW72T3BlbkFJ111111111111111114WKPqZbPZt6vkapBTn77(재발급)
AIza11111111111111111111111SyDFCsEIzN6AW6_HJP1111111111111111111111111Jix9EjRObjLIgVEGs(qwer.js)


lens key


AIza11111111111111111111111SyDP9XHEi_3RFpD1111111111111111111111111D2c6jKcP8o7L8tGmPShM
AIzaSyD111111111111111111111111LIcg-VsVJ3Rg11111111111111111111111sW8-cI76Zrsp1_qkTBAA(재발급)


클라우드 키



<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 먼저 jQuery를 포함합니다 -->
    <script src="https://code.jquery.com/jquery-3.7.1.js"></script>

    <!-- Bootstrap CSS를 포함합니다 -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Bootstrap JS를 jQuery 이후에 포함합니다 -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"></script>

    <!-- jQuery 이후에 다른 스크립트를 포함합니다 -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.2/jquery.min.js"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.js"></script>
    <style>
        .fakeimg {
            height: 200px;
            background: #aaa;
        }

        body {
            background-color: rgb(52, 52, 57);
            color: white;
            margin: 0;
        }

        .nav {
            height: 60px;
            border-bottom: 1px solid black;
            display: flex;
            align-items: center;
            justify-content: space-between;
            background-color: #2a2a30;
            margin: 0;
            padding: 0 20px;
        }

        .nav-right-items {
            display: flex;
        }

        .nav-item,
        .company-name {
            color: rgb(255, 255, 255);
        }

        .nav-item {
            margin-left: 10px;
        }

        .company-name {
            margin-left: 20px;
            font-weight: bold;
        }

        .title {
            text-align: center;
            font-size: 3.5rem;
            margin-top: 80px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .title img {
            max-width: 100px;
            max-height: 100px;
            margin-right: 20px;
        }

        .subtitle {
            text-align: center;
            font-size: 1.25rem;
            font-weight: 300;
        }

        .main {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            margin-right: 50px;
            margin-top: -60px;
        }

        .prices {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: row;
            gap: 20px;
        }

        .price-item {
            position: relative;
            width: 300px;
            height: 300px;
            border: 1px solid rgb(129, 127, 127);
            margin: 20px;
            border-radius: 4px;
            background-color: rgb(255, 255, 255);
            background-position: center;
            background-size: cover;
            background-repeat: no-repeat;
        }

        .price-item-title {
            font-size: 1.5rem;
            background: rgb(232, 234, 237);
            text-align: center;
            height: 53px;
            line-height: 53px;
            border-bottom: 1px solid black;
            color: black;
        }

        .price-item-button {
            padding: .5rem 1rem;
            font-size: 1.25rem;
            line-height: 1.5;
            border-radius: .3rem;
            color: #ff0000;
            background-color: transparent;
            background-image: none;
            border-color: #000000;
            position: relative;
            left: -85px;
            margin-top: 0px;
            transform: translateX(43%);
        }

        .price-item-button--active {
            background-color: #d62222;
            color: white;
        }

        #fileform {
            margin-top: 0;
        }

        #results,
        #resultr {
            background-color: rgb(255, 255, 255);
            border: 1px solid rgb(110, 109, 109);
            margin-top: 20px;
            margin-left: 20px;
        }

        #textkan {
            margin-top: -190px;
            margin-right: 380px;
            text-align: center;
            border: none;
            resize: none;
        }

        #textkaan {
            margin-top: -55px;
            margin-right: -380px;
            text-align: center;
            border: none;
            resize: none;
        }

        #gimage {
            margin: 20px;
        }

        .upload-section {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
            margin-left: 85px;
            margin-top: 80px;
        }

        .result-section {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
        }

        /* "그림에 대해 말씀하세요" 섹션의 스타일 수정 */
        .input-group.mb-3 {
            max-width: 300px;
            margin: auto;
        }

        .form-control {
            width: 100%;
        }

        .btn.btn-success {
            width: 100%;
        }

        .input-group.mb-3 {
            max-width: 300px;
            margin: auto;
            display: none;
        }
    </style>
</head>

<body>
    <!-- 네비게이션 및 메인 섹션 -->
    <div class="nav">
        <div class="company-name">
            Image Analysis
        </div>
    </div>
    <div class="main">
        <!-- 이미지 분석 섹션 -->
        <div class="title">
            <img src="./현미경.png" alt="이미지">
            Image Analysis
        </div>
        <div class="subtitle">이미지 분석 웹 페이지입니다.<br> 파일 선택에서 분석하고자 하는 이미지를 선택한 뒤 Submit을 눌러주세요.</div>
        <div class="prices">
            <!-- 이미지 표시 섹션 -->
            <div class="price-item" id="image-container"></div>
            <!-- 결과 표시 섹션 -->
            <div class="result-section">
                <textarea name="results" id="results" cols="50" rows="10" style="display: none;"></textarea>
                <textarea name="resultr" id="resultr" cols="50" rows="10" style="display: none;"></textarea>
            </div>
            <img id="gimage" style="border: 5px solid #555; background-color: rgb(255, 255, 255); width: 300px; height: 300px; ">
        </div>
        <!-- 이미지 업로드 및 분석 섹션 -->
        <div class="upload-section">
            <div>
                <!-- 이미지 업로드 폼 -->
                <input type="file" name="fileField" id="fileField" onChange="uploadFiles(this.files)">
                <!-- 이미지 타입 선택 폼 -->
                <form id="fileform" action="">
                    <select name="type" id="detectionType" style="display: none;">
                        <option value="LABEL_DETECTION" selected>LABEL_DETECTION</option>
                    </select>
                </form>
            </div>
            <!-- 이미지 분석 버튼 -->
            <button class="price-item-button price-item-button--active" onclick="Send()">Submit</button>
            <!-- 추가 버튼 (예: 대답하기) -->
            <button class="btn btn-success" type="submit" onclick="Draw()" id="btnSend" style="display: none;">대답하기</button>
        </div>
        <textarea name="textkan" id="textkan" cols="37" rows="2">↑선택한 이미지</textarea>
        <textarea name="textkaan" id="textkaan" cols="37" rows="2">↑비슷한 이미지</textarea>
    </div>

    <!-- 그림에 대해 말씀하세요 섹션 -->
    <div class="input-group mb-3">
        <input type="text" class="form-control" placeholder="그림에 대해 말씀하세요" id="imgMsg">
    </div>

    <!-- 추가 스크립트 -->
    <script src="chat.js"></script>
    <script>
        // 이미지 관련 코드 및 함수
        var VISION_API_KEY = "111111111111111111111111111111111111111";
        var CV_URL = 'https://vision.googleapis.com/v1/images:annotate?key=' + VISION_API_KEY;
        var imagestring = "";

        // 파일 처리 함수
        function processFile(event) {
            var content = event.target.result;
            imagestring = content.replace('data:image/jpeg;base64,', '');

            // 이미지를 미리보기로 표시
            var imageContainer = document.getElementById('image-container');
            imageContainer.style.backgroundImage = 'url(' + content + ')';
            imageContainer.style.backgroundPosition = 'center';
            imageContainer.style.backgroundSize = 'cover';
            imageContainer.style.backgroundRepeat = 'no-repeat';
        }

        // 파일 업로드 함수
        function uploadFiles(files) {
            var file = files[0];
            var reader = new FileReader();
            reader.onloadend = function (event) {
                processFile(event);
                // 이미지 업로드 시 select를 LABEL_DETECTION으로 변경
                document.getElementById('detectionType').value = 'LABEL_DETECTION';
            };
            reader.readAsDataURL(file);
        }

        // 이미지 분석 및 결과 표시 함수
        function Send() {
            var detectionType = $('#fileform select[name=type]').val();
            console.log("Detection Type:", detectionType);

            var request = {
                requests: [{
                    image: {
                        content: imagestring
                    },
                    features: [{
                        type: detectionType,
                        maxResults: 200
                    }]
                }]
            };

            $.ajax({
                type: "POST",
                url: CV_URL,
                headers: {
                    "Accept": "application/json",
                    "Content-Type": "application/json"
                },
                data: JSON.stringify(request),
                contentType: "application/json; charset=utf-8"
            }).done(function (response) {
                // displayJSON 함수 호출 (가정: 이 함수가 정의되어 있다고 가정)
                displayJSON(response);

                // resultr 텍스트 영역의 내용을 가져와서 imgMsg 입력 필드에 설정
                var resultrText = $('#resultr').val();
                $('#imgMsg').val(resultrText);

                // "btnSend" 버튼 클릭
                $('#btnSend').click();
            }).fail(function (error) {
                alert("!/error  js에서 에러발생: " + error);
            });
        }

        // displayJSON 함수 추가
        function displayJSON(data) {
            var contents = JSON.stringify(data, null, 4);
            $('#results').text(contents);

            var dlabels = "";
            var labels = data.responses[0].labelAnnotations;

            console.log(labels);

            labels.forEach(function (label) {
                dlabels += label.description + "\n";
            });
            $('#resultr').text(dlabels);
        }
    </script>
</body>

</html>





chat.js

var OPENAI_API_KEY =
'sk-Y62m9gPDfUP111111111111111111111111111111PK0t3KW72T3BlbkFJ4WKPqZ1111111111111111111111111111111111bPZt6vkapBTn77';

function Send(){

  var sQuestion = txtMsg.value;
  var data = {
    model: "text-davinci-003",
    prompt: sQuestion,
    max_tokens: 2048,
    temperature: 0
}  
$.ajax({
  type: "POST",
  url: 'https://api.openai.com/v1/completions',
  headers:{
    "Accept" : "application/json",
    "Content-Type": "application/json", 
    "Authorization": "Bearer " +  OPENAI_API_KEY },
  data: JSON.stringify(data),

}).done(function(response) {


     var sanswer = response.choices[0].text
     txtOut.value = sanswer

}).fail(function(error) {
  alert("!/js/user.js에서 에러발생: " + error.statusText);
  console.log(error)
});
}

function Draw(){

  var sQuestion = imgMsg.value;
  var data = {
    prompt: sQuestion,
    n:2,
    size: "512x512"
}  
$.ajax({
  type: "POST",
  url: 'https://api.openai.com/v1/images/generations',
  headers:{
    "Accept" : "application/json",
    "Content-Type": "application/json", 
    "Authorization": "Bearer " +  OPENAI_API_KEY },
  data: JSON.stringify(data),

}).done(function(response) {

      gimage.src = response.data[0].url
      gimage2.src = response.data[0].url

}).fail(function(error) {
  alert("!/js/user.js에서 에러발생: " + error.statusText);
  console.log(error)
});
}


        let ChatObject = {
                getAnswer: function() {
            
                  alert("$.ajax 실행")
                  var data = {
                        model: "text-davinci-003",
                        prompt: "가을에 듣기 좋은 음악이 뭘까",
                        max_tokens: 2048,
                        temperature: 0
                  }  
                  $.ajax({
                    type: "POST",
                    url: 'https://api.openai.com/v1/completions',
                    headers:{
                        "Accept" : "application/json",
                        "Content-Type": "application/json", 
                        "Authorization": "Bearer " +  OPENAI_API_KEY },
                    data: JSON.stringify(data),
            
                  }).done(function(response) {
            
                         console.log(response)
                         alert(response.choices[0].text)
            
                  }).fail(function(error) {
                    alert("!/js/user.js에서 에러발생: " + error.statusText);
                    console.log(error)
                  });
                },
               }
              
              //  ChatObject.getAnswer();



qwer.js

var VISION_API_KEY = "AIz1111111111111111111111aSyDFCsEIzN6AW6_HJ111111111111111111111111PJix9EjRObjLIgVEGs";
var CV_URL = 'https://vision.googleapis.com/v1/images:annotate?key=' + VISION_API_KEY;

var imagestring = null;
var labels = null; // labels 변수를 전역 스코프에서 선언

function processFile(event) {
    var content = event.target.result;
    imagestring = content.replace('data:image/jpeg;base64,', '');
}

function uploadFiles(files) {
    var file = files[0];
    var reader = new FileReader();
    reader.onloadend = processFile;
    reader.readAsDataURL(file);
}

function Send() {
    var request = {
        requests: [{
            image: {
                content: imagestring
            },
            features: [{
                type: $('#fileform [name=type]').val(),
                maxResults: 200
            }]
        }]
    };

    $.ajax({
        type: "POST",
        url: CV_URL,
        headers: {
            "Accept": "application/json",
            "Content-Type": "application/json"
        },
        data: JSON.stringify(request),
        contentType: "application/json; charset=utf-8"
    }).done(displayJSON)
        .fail(function (error) {
            alert("!/error  js에서 에러발생: " + error);
        });
}

function displayJSON(data) {
    var contents = JSON.stringify(data, null, 4);
    $('#results').text(contents);

    // label detect인 경우만 해당됨
    var dlabels = "";
    labels = data.responses[0].labelAnnotations;
    console.log(labels);
    labels.forEach(function (label) {
        dlabels += label.description + "\n";
    });
    $('#resultr').text(dlabels);
}
