# Simply Course Map for McGill
This Webapp would not be possible without the input from [Sixian Li](https://github.com/Deerhound579). If you like this project, make sure that you start Sixian' repo: [https://github.com/Deerhound579/mcgill-course-map](https://github.com/Deerhound579/mcgill-course-map).

Repo for the backend: [https://github.com/jacobthebanana/mcgill-course-map/tree/dockerable](https://github.com/jacobthebanana/mcgill-course-map/tree/dockerable).

<html>
    <body>
        <form action="https://course-map.api.tianshome.com/" target="_blank" name="form" id="form1" method="get">
            <label for="courses">Courses that you want to take (*)</label><br>
            <input type="text" id="courses" name="courses" value="MATH 236, COMP 302, COMP 350"><br>
            <label for="courses_excluded">Courses that you are exempt from or have already taken (*)</label><br>
            <input type="text" id="courses_excluded" name="courses_excluded" value="MATH 139, COMP 202"><br>
            <br>
            <input type="submit" value="Submit ✔️">
        </form>
    </body>
</html>


---
Disclaimer: This project is neither endorsed by nor affilited to McGill University or its subsidaries. The use of this product does not gurantee eligibility for any course. As stated in the license, its authors should not be held liable for any loss due to the use of this product. Your input might be transferred outside of Canada for processing.
