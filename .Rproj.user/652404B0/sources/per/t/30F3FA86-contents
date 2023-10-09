summary_age <- childrens_mythology %>%
  summarize(mean = mean(Date, na.rm = TRUE),
            std_dev = sd(Date, na.rm = TRUE))
childrens_mythology %>%
  group_by(Region)
study %>%
  group_by(Region) %>%
  summarize(avg_score = mean(na.rm = Tier_Score))
tier_region <- study %>%
  group_by(Region) %>%
  summarize(count = n())
level_region <- study %>%
  group_by(Region, Tier_Score) %<%
  summarise(count = n())
level_region <- study %>% 
  group_by(Region, Tier_Score) %>% 
  summarize(count = n())
