
public class GitPersona
{
    private string _name = 'CodeKnee';
    private List<string> _codingLanguages = new List<string>
                                              {C#, C++, Java, Python, Typescript, HTML, CSS, Javascript, SQL};

    private List<string> _interests = new List<string>();

    public GitPersona()
    {
      AddInterests();
    }

    public void AddInterests()
    {
       _interests.add('Video Game Development');
       _interests.add('Software Development');
       _interests.add('Web Development');
    }

}

