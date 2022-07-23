usr/bin/node

function hammingDist(str1, str2)
{
    let i = 0, count = 0;
    while (i < str1.length)
    {
        if (str1[i] != str2[i])
            count++;
        i++;
    }
    return count;
}
    var Name = "Aniket";
    var Email = "aabagate1120@gmail.com";
    var Slackusername = "@Aniket";
    var Biostack = "Vaccine Informatics";
    var Twitter = "@Aniket";

    console.log(Name +',' + Email +','+ Slackusername +','+ Biostack + ","+ 
