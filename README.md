


    public class GitPersona
    {
        #region private variables
        private List<string> _interests = new List<string>();
        private string _name = 'CodeKnee';
        private List<string> _codingLanguages = new List<string>
                                                  {C#, C++, Java, Python, Typescript, HTML, CSS, Javascript, SQL};
        #endregion private variables

        #region constructors
        public GitPersona()
        {
          AddInterests();
        }
        #endregion contructors

        #region utility functions
        public void AddInterests()
        {
           _interests.add('Video Game Development');
           _interests.add('Software Development');
           _interests.add('Web Development');
        }
        #endregion utility functions

    }

