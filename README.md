<h1 align="center">
<a href="https://git.io/typing-svg">
<img src="https://readme-typing-svg.herokuapp.com?font=ubuntu&size=23&duration=2000&pause=1000&color=F700E1&center=true&width=435&lines=Hello+hacker+%E2%98%A3;Welcome+in+my+github++%F0%9F%A4%97;Lets+visit+my+repo+%F0%9F%A4%AF;Dont+forget+to+join+%40repproject++%F0%9F%92%A8">
</a>
</h1>  
<pre>
Hi i'm Rep, Owner Of :
   ___           ___             _         __ 
  / _ \___ ___  / _ \_______    (_)__ ____/ /_      
 / , _/ -_) _ \/ ___/ __/ _ \  / / -_) __/ __/ 	   
/_/|_|\__/ .__/_/  /_/  \___/_/ /\__/\__/\__/ 
        /_/                |___/   
Telegram : @CallMeRep |  Facebook : callmerep.real
</pre>

<br>

```golang
package README.md

import "replogger"

type Profile struct {
	Language []string
	Other    []string
}

type BioData struct {
	Rep *Profile
}

func GetSkills() *Profile {
	return &Profile{
		Language: []string{"Go", "Python", "JavaScript", "C++"},
		Other:    []string{"Conccurency Spesialist", "Cloud Engineer", "Big Data Specialist", "Cyber Security Aalyst"},
	}
}

func Init() *BioData {
	biodata := BioData{
		Rep: GetSkills(),
	}
	return &biodata
}

func (b *BioData) Welcome() {
	log := replogger.Data{
		Info: func(f replogger.InfoPrinter) {
			f.Show("Languages", b.Rep.Language)
			f.Show("Other Skills", b.Rep.Other)
		},
	}
	log.Execute().WithCustomOptions()
}

func main() {
	biodata := Init()
	biodata.Welcome()
}
```

***
<br>
<img align='right' src='https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=t101804&theme=nord_dark' width='280px'>
<img align='left' src='http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=t101804&theme=nord_dark' width='555px'> 
