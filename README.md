# task_2.1
task_2.1

public class Main {

    public static void main(String[] args) {

       String words [] = {"Мама", "Мыла", "Раму"};

        String word1 = "";
        String word2 = "";
        String word3 = "";


      for (int i = 0; i < words.length; i++) {
          word1 = words[i];

          for (int j = 0; j < words.length; j++) {
              word2 = words[j];
              if (word2 != word1) {

                for (int u = 0; u < words.length; u++) {
                  word3 = words[u];
                  if (word3 != word1 && word3 != word2) {

                      System.out.println(word1 + word2 + word3);
                  }
                }
              }
          }
      }
    }
}
