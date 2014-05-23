task :sass do
  sh "sass --watch -t compressed scss/stylesheet.scss:css/stylesheet.css"
end

task :build do
  Dir["recipes/*"].sort_by{ |r| r.downcase }.each do |folder|
    folder_name = folder.split("/")[1]
    puts "<h1>#{folder_name.capitalize}</h1>"

    puts "<table>"
    puts "<tr>"
    count = 0
    Dir["#{folder}/*"].sort_by{ |r| r.downcase }.each do |recipe|
      recipe = recipe[8, recipe.length]
      recipe_name = recipe.split("/")[1].split("_").map { |x| x.capitalize }.join(" ")
      puts '<td data-name="' << recipe << '">' << recipe_name << "</td>"
      count += 1
      if count == 3
        puts "</tr>"
        puts "<tr>"
        count = 0
      end
    end
    puts "</tr>"
    puts "</table>"
  end
end