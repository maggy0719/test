<!DOCTYPE html>
<html>

<head>
    <style>
        form {
            width: 500px;
            margin: 15px
        }
    </style>
</head>

<body bgcolor="E0E0FF">


    <form method="get" action="這次.html">
        <h1 align="center">會員申請表</h1>
        <fieldset>
            <legend>
                <h3>個人相關資料</h3>
            </legend>
            <p>帳號:<input type="text" name="username" size="20"></br></p>
            <p>密碼:<input type="password" name="password" size="20"></br></p>
            <p>姓名:<input type="text" name="name" size="20"></p>
            </br>
            姓別:<input type="radio" name="gender" value="男">男生
            <input type="radio" name="gender" value="女">女生
            <hr />
            <blockquote> 學歷:
                <select size="1" name="age">
                    <option>國小</option>
                    <option>國中</option>
                    <option>高中</option>
                    <option>大學</option>
                </select>
            </blockquote>
            <ol>
                <li>興趣(可複選):
                    <input type="checkbox" name="interest" value="看書">看書
                    <input type="checkbox" name="interest" value="上網">上網
                    <input type="checkbox" name="interest" value="運動">運動
                    <input type="checkbox" name="interest" value="唱歌">唱歌
                    <input type="checkbox" name="interest" value="聽音樂">聽音樂</li></br>
                <li>備註:</br>
                    <textarea name="good" cols="40" roes="2" wrap="virtual"></textarea>
                </li>
            </ol>
        </fieldset>
        <input type="submit" name="S1" value="送出資料">
        <input type="reset" name="S1" value="重寫">
    </form>
    </table>
</body>

</html>
