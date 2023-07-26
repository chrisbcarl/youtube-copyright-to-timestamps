# youtube-copyright-to-timestamps
Convert the text from the Youtube Studio copyright section into usable timestamps in the description!

# Usage
1. take something that looks like ![sample.png](./sample.PNG)
2. Drag from the "Content used" | "Impact on the video" columns, and paste it in a file like [sample.txt](./sample.txt)
3. run the following to get nice output
    ```bash
    python main.py sample.txt
    ```
    ```txt
    00:04:06 - Rome In Silver - Fool
    00:05:03 - Kanye West - Fade
    00:05:58 - Justice - Helix
    00:08:01 - Skrillex, Starrah, Four Tet - Butterflies (Extended Mix)
    00:10:11 - Madeon - Technicolor
    00:12:17 - Justice, Simian - We Are Your Friends (Justice Vs. Simian)
    00:21:26 - Daft Punk - One More Time (Radio Edit)
    00:23:14 - Virtual Self - ゴースト・ヴォイセズ
    00:24:48 - Modjo - Lady (Hear Me Tonight) (Hear Me Tonight)
    00:26:52 - DJ Snake - U Are My High
    00:28:41 - Justice - Safe and Sound (WWW)
    ```