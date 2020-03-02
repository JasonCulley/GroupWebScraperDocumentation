## Jason Culley's Participation in The Group Web Scraper

window = tk.Tk()

class GUI:
    def RunGUI(self):

        l1 = tk.Label(window, text="Enter website name here ")
        l2 = tk.Label(window, text="Enter checkrate here (in seconds) ")
        l3 = tk.Label(window, text="Enter SID here ")
        l4 = tk.Label(window, text="Enter Twilio Authorization here ")
        l5 = tk.Label(window, text="Enter Twilio phone number here ")
        l6 = tk.Label(window, text="Enter user phone number here ")

        self.entWebsite = tk.Entry(window, text="Hello World")
        self.entCheckRate = tk.Entry(window)
        self.entSID = tk.Entry(window)
        self.entAuth = tk.Entry(window)
        self.entTwilPhone = tk.Entry(window)
        self.entUserPhone = tk.Entry(window)
        
        button = tk.Button(window, text="Finish", width=25, command=self.end)

        l1.grid(row=0, column=0, pady=2)
        l2.grid(row=1, column=0, pady=2)
        l3.grid(row=2, column=0, pady=2)
        l4.grid(row=3, column=0, pady=2)
        l5.grid(row=4, column=0, pady=2)
        l6.grid(row=5, column=0, pady=2)

        self.entWebsite.grid(row=0, column=2, pady=2)
        self.entCheckRate.grid(row=1, column=2, pady=2)
        self.entSID.grid(row=2, column=2, pady=2)
        self.entAuth.grid(row=3, column=2, pady=2)
        self.entTwilPhone.grid(row=4, column=2, pady=2)
        self.entUserPhone.grid(row=5, column=2, pady=2)

        button.grid(row=6, column=1)

        window.mainloop()


#I wrote all that because we need a GUI to be user friendly. I contributed on the conceptual development along the way as well as the twilio dictionary section, but I know collaborating doesn't count for anything. Just thought I'd mention it.

