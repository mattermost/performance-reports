### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| CommandWebhookStore.Cleanup | avg | 1ms | 17ms | 16ms | 2306.74
| ChannelStore.GetMembers | avg | 3ms | 26ms | 23ms | 778.88
| TokenStore.Cleanup | avg | 1ms | 5ms | 4ms | 590.45
| UserStore.GetMany | avg | 12ms | 74ms | 62ms | 531.82
| UserStore.GetProfilesInChannel | avg | 45ms | 156ms | 111ms | 248.27
| BotStore.Get | avg | 17ms | 46ms | 29ms | 171.64
| PreferenceStore.DeleteCategoryAndName | avg | 4ms | 9ms | 5ms | 137.42
| UserStore.GetProfilesNotInChannel | avg | 67ms | 151ms | 84ms | 124.58
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 4ms | 8ms | 4ms | 105.69
| ChannelStore.CreateSidebarCategory | avg | 25ms | 50ms | 25ms | 98.18
| PostStore.GetPostReminders | avg | 4ms | 8ms | 4ms | 94.93
| ChannelStore.Save | avg | 50ms | 93ms | 43ms | 85.34
| ThreadStore.Get | avg | 49ms | 89ms | 40ms | 82.37
| PostStore.SetPostReminder | avg | 5ms | 9ms | 4ms | 73.01
| StatusStore.UpdateExpiredDNDStatuses | avg | 3ms | 5ms | 2ms | 57.82
| UserStore.GetByUsername | avg | 47ms | 73ms | 26ms | 55.78
| JobStore.Get | avg | 47ms | 73ms | 26ms | 54.79
| JobStore.UpdateOptimistically | avg | 4ms | 6ms | 2ms | 49.58
| JobStore.GetCountByStatusAndType | avg | 51ms | 76ms | 25ms | 48.65
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 59ms | 83ms | 24ms | 40.54
| ChannelStore.GetChannelsByUser | avg | 36ms | 50ms | 14ms | 38.73
| PostAcknowledgementStore.GetForPost | avg | 46ms | 63ms | 17ms | 37.17
| JobStore.GetNewestJobByStatusesAndType | avg | 53ms | 72ms | 19ms | 35.84
| ChannelStore.GetChannelUnread | avg | 29ms | 39ms | 10ms | 35.01
| PostStore.SearchPostsForUser | avg | 138ms | 186ms | 48ms | 34.81
| PostStore.GetPostsByThread | avg | 50ms | 67ms | 17ms | 33.75
| TeamStore.GetTotalMemberCount | avg | 283ms | 363ms | 80ms | 28.31
| PostStore.GetPostReminderMetadata | avg | 42ms | 54ms | 12ms | 28.29
| PostStore.GetPostsAfter | avg | 41ms | 52ms | 11ms | 27.05
| SessionStore.GetSessionsExpired | avg | 60ms | 76ms | 16ms | 26.72
| UserStore.GetUnreadCount | avg | 38ms | 48ms | 10ms | 26.31
| ReactionStore.GetForPost | avg | 53ms | 67ms | 14ms | 26.22
| StatusStore.SaveOrUpdate | avg | 61ms | 77ms | 16ms | 26.13
| PluginStore.List | avg | 67ms | 84ms | 17ms | 25.47
| ThreadStore.GetThreadFollowers | avg | 51ms | 64ms | 13ms | 25.33
| UserAccessTokenStore.GetByToken | avg | 36ms | 45ms | 9ms | 24.80
| PostStore.Get | avg | 87ms | 108ms | 21ms | 24.07
| ThreadStore.GetThreadForUser | avg | 69ms | 85ms | 16ms | 23.05
| PostStore.GetSingle | avg | 48ms | 59ms | 11ms | 22.88
| LinkMetadataStore.Get | avg | 49ms | 60ms | 11ms | 22.39
| ChannelStore.AutocompleteInTeamForSearch | avg | 262ms | 319ms | 57ms | 21.74
| ChannelStore.GetMemberForPost | avg | 60ms | 73ms | 13ms | 21.62
| TeamStore.Get | avg | 48ms | 58ms | 10ms | 21.04
| ChannelStore.GetMembersForUser | avg | 48ms | 58ms | 10ms | 20.90
| ChannelStore.GetChannels | avg | 49ms | 59ms | 10ms | 20.54
| PostPersistentNotificationStore.GetSingle | avg | 51ms | 61ms | 10ms | 19.77
| ThreadStore.GetThreadsForUser | avg | 57ms | 68ms | 11ms | 19.38
| ThreadStore.GetMembershipForUser | avg | 47ms | 56ms | 9ms | 19.27
| ThreadStore.GetThreadUnreadReplyCount | avg | 57ms | 68ms | 11ms | 19.17
| StatusStore.GetByIds | avg | 58ms | 69ms | 11ms | 18.99
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 38ms | 45ms | 7ms | 18.56
| ThreadStore.GetTotalUnreadThreads | avg | 38ms | 45ms | 7ms | 18.26
| WebhookStore.GetOutgoingByTeam | avg | 55ms | 65ms | 10ms | 18.07
| ThreadStore.GetTotalThreads | avg | 39ms | 46ms | 7ms | 18.04
| TeamStore.GetTeamsForUser | avg | 28ms | 33ms | 5ms | 17.80
| PostStore.GetPostsBefore | avg | 51ms | 60ms | 9ms | 17.52
| PreferenceStore.Get | avg | 46ms | 54ms | 8ms | 17.49
| SessionStore.Save | avg | 34ms | 40ms | 6ms | 17.46
| GroupStore.GetGroups | avg | 53ms | 62ms | 9ms | 17.12
| PostAcknowledgementStore.GetForPosts | avg | 65ms | 76ms | 11ms | 16.98
| PostPriorityStore.GetForPosts | avg | 67ms | 78ms | 11ms | 16.48
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 43ms | 50ms | 7ms | 16.38
| ChannelStore.CreateDirectChannel | avg | 143ms | 166ms | 23ms | 16.10
| PostStore.GetPostsSince | avg | 70ms | 81ms | 11ms | 15.76
| EmojiStore.GetByName | avg | 51ms | 59ms | 8ms | 15.70
| ThreadStore.GetTotalUnreadMentions | avg | 39ms | 45ms | 6ms | 15.32
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 39ms | 45ms | 6ms | 15.30
| UserStore.GetProfilesByUsernames | avg | 40ms | 46ms | 6ms | 15.07
| TeamStore.GetActiveMemberCount | avg | 367ms | 422ms | 55ms | 15.00
| ChannelStore.SearchGroupChannels | avg | 60ms | 69ms | 9ms | 14.93
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 101ms | 116ms | 15ms | 14.84
| TeamStore.GetChannelUnreadsForAllTeams | avg | 42ms | 48ms | 6ms | 14.16
| ChannelStore.GetPinnedPostCount | avg | 51ms | 58ms | 7ms | 13.62
| FileInfoStore.Get | avg | 37ms | 42ms | 5ms | 13.54
| TeamStore.GetTeamsByUserId | avg | 46ms | 52ms | 6ms | 12.93
| ChannelStore.Get | avg | 93ms | 105ms | 12ms | 12.88
| SessionStore.GetLRUSessions | avg | 32ms | 36ms | 4ms | 12.61
| ChannelStore.GetAllChannelMembersForUser | avg | 32ms | 36ms | 4ms | 12.58
| ThreadStore.GetTeamsUnreadForUser | avg | 49ms | 55ms | 6ms | 12.25
| PostStore.GetEtag | avg | 66ms | 74ms | 8ms | 12.10
| UserStore.Count | avg | 274ms | 306ms | 32ms | 11.70
| UserTermsOfServiceStore.GetByUser | avg | 43ms | 48ms | 5ms | 11.53
| TeamStore.GetAllPage | avg | 44ms | 49ms | 5ms | 11.44
| ChannelStore.GetFileCount | avg | 36ms | 40ms | 4ms | 11.00
| ChannelStore.GetMemberLastViewedAt | avg | 36ms | 40ms | 4ms | 10.98
| UserStore.AutocompleteUsersInChannel | avg | 415ms | 459ms | 44ms | 10.61
| ChannelStore.UpdateSidebarCategories | avg | 137ms | 151ms | 14ms | 10.24
| UserStore.GetProfileByIds | avg | 30ms | 33ms | 3ms | 10.13
| ChannelStore.GetGuestCount | avg | 69ms | 76ms | 7ms | 10.10
| JobStore.GetAllByStatus | avg | 50ms | 55ms | 5ms | 10.00
| UserStore.Search | avg | 203ms | 223ms | 20ms | 9.86
| UserStore.GetForLogin | avg | 34ms | 37ms | 3ms | 8.80
| PreferenceStore.GetAll | avg | 59ms | 64ms | 5ms | 8.43
| UserStore.GetAllProfiles | avg | 36ms | 39ms | 3ms | 8.31
| SessionStore.Get | avg | 48ms | 51ms | 3ms | 6.25
| GroupStore.GetByName | avg | 33ms | 35ms | 2ms | 5.98
| ChannelStore.Autocomplete | avg | 2.257s | 2.386s | 129ms | 5.71
| PostStore.GetPosts | avg | 38ms | 40ms | 2ms | 5.30
| ChannelStore.SaveMember | avg | 227ms | 239ms | 12ms | 5.29
| ChannelStore.CreateInitialSidebarCategories | avg | 63ms | 66ms | 3ms | 4.74
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 65ms | 68ms | 3ms | 4.62
| ChannelStore.GetByName | avg | 51ms | 53ms | 2ms | 3.96
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 52ms | 54ms | 2ms | 3.86
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| CommandWebhookStore.Cleanup | p99 | 5ms | 98ms | 93ms | 1878.79
| ChannelStore.GetMembers | p99 | 5ms | 50ms | 45ms | 909.09
| ChannelStore.CreateSidebarCategory | p99 | 98ms | 480ms | 382ms | 387.82
| LinkMetadataStore.Save | p99 | 9ms | 40ms | 31ms | 353.17
| PostStore.GetPostReminders | p99 | 23ms | 94ms | 71ms | 310.04
| PreferenceStore.DeleteCategoryAndName | p99 | 23ms | 93ms | 70ms | 297.87
| PostStore.SetPostReminder | p99 | 24ms | 93ms | 69ms | 292.68
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 24ms | 93ms | 69ms | 287.50
| UserStore.GetProfilesNotInChannel | p99 | 245ms | 945ms | 700ms | 286.30
| UserStore.GetProfilesInChannel | p99 | 457ms | 1.45s | 993ms | 217.06
| ChannelStore.Save | p99 | 325ms | 885ms | 560ms | 172.32
| ThreadStore.Get | p99 | 434ms | 954ms | 520ms | 119.95
| UserStore.GetMany | p99 | 214ms | 457ms | 243ms | 113.55
| BotStore.Get | p99 | 208ms | 422ms | 214ms | 102.88
| TokenStore.Cleanup | p99 | 5ms | 10ms | 5ms | 101.01
| StatusStore.UpdateExpiredDNDStatuses | p99 | 43ms | 86ms | 43ms | 100.00
| TeamStore.GetTotalMemberCount | p99 | 496ms | 945ms | 449ms | 90.51
| RoleStore.ChannelHigherScopedPermissions | p99 | 180ms | 333ms | 153ms | 84.88
| JobStore.UpdateOptimistically | p99 | 31ms | 55ms | 24ms | 77.42
| JobStore.Save | p99 | 40ms | 67ms | 27ms | 66.67
| PostAcknowledgementStore.GetForPost | p99 | 495ms | 823ms | 328ms | 66.21
| PostStore.GetPostsByThread | p99 | 498ms | 747ms | 249ms | 50.04
| JobStore.UpdateStatusOptimistically | p99 | 46ms | 67ms | 21ms | 45.45
| PostStore.SearchPostsForUser | p99 | 1.066s | 1.529s | 463ms | 43.42
| JobStore.Get | p99 | 620ms | 851ms | 231ms | 37.26
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 496ms | 669ms | 173ms | 34.91
| LinkMetadataStore.Get | p99 | 499ms | 672ms | 173ms | 34.64
| PostStore.GetSingle | p99 | 496ms | 664ms | 168ms | 33.90
| ChannelStore.GetChannels | p99 | 493ms | 651ms | 158ms | 32.02
| TeamStore.Get | p99 | 495ms | 639ms | 144ms | 29.07
| EmojiStore.GetByName | p99 | 499ms | 642ms | 143ms | 28.68
| GroupStore.GetGroups | p99 | 526ms | 675ms | 149ms | 28.34
| PostStore.GetPostsBefore | p99 | 497ms | 627ms | 130ms | 26.13
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 980ms | 1.234s | 254ms | 25.92
| ChannelStore.GetMemberForPost | p99 | 634ms | 790ms | 156ms | 24.61
| PostStore.GetPostsSince | p99 | 603ms | 744ms | 141ms | 23.36
| ChannelStore.GetChannelUnread | p99 | 370ms | 454ms | 84ms | 22.71
| ChannelStore.GetMembersForUser | p99 | 486ms | 594ms | 108ms | 22.21
| PreferenceStore.Get | p99 | 492ms | 601ms | 109ms | 22.14
| ThreadStore.GetTeamsUnreadForUser | p99 | 628ms | 763ms | 135ms | 21.51
| ThreadStore.GetThreadFollowers | p99 | 602ms | 726ms | 124ms | 20.61
| PostPersistentNotificationStore.GetSingle | p99 | 528ms | 635ms | 107ms | 20.28
| ThreadStore.GetThreadsForUser | p99 | 614ms | 738ms | 124ms | 20.18
| ThreadStore.GetThreadUnreadReplyCount | p99 | 637ms | 754ms | 117ms | 18.36
| WebhookStore.GetOutgoingByTeam | p99 | 608ms | 718ms | 110ms | 18.09
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.975s | 2.327s | 352ms | 17.82
| JobStore.GetNewestJobByStatusesAndType | p99 | 610ms | 717ms | 107ms | 17.54
| ChannelStore.GetGuestCount | p99 | 656ms | 768ms | 112ms | 17.08
| ThreadStore.GetMembershipForUser | p99 | 489ms | 568ms | 79ms | 16.16
| PreferenceStore.GetAll | p99 | 529ms | 612ms | 83ms | 15.70
| ReactionStore.GetForPost | p99 | 626ms | 720ms | 94ms | 15.02
| PostStore.GetEtag | p99 | 667ms | 767ms | 100ms | 15.00
| ChannelStore.GetMember | p99 | 79ms | 90ms | 11ms | 13.94
| UserAccessTokenStore.GetByToken | p99 | 413ms | 467ms | 54ms | 13.09
| TeamStore.GetMember | p99 | 48ms | 54ms | 6ms | 12.39
| TeamStore.SaveMember | p99 | 666ms | 748ms | 82ms | 12.30
| JobStore.GetAllByStatus | p99 | 494ms | 550ms | 56ms | 11.34
| ChannelStore.GetChannelsByUser | p99 | 435ms | 483ms | 48ms | 11.03
| ChannelStore.CreateInitialSidebarCategories | p99 | 495ms | 549ms | 54ms | 10.90
| UserStore.AutocompleteUsersInChannel | p99 | 1.948s | 2.129s | 181ms | 9.29
| UserStore.IsEmpty | p99 | 286ms | 312ms | 26ms | 9.08
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 38ms | 41ms | 3ms | 7.95
| SessionStore.Save | p99 | 414ms | 446ms | 32ms | 7.73
| ChannelStore.Get | p99 | 831ms | 894ms | 63ms | 7.58
| PostAcknowledgementStore.GetForPosts | p99 | 908ms | 970ms | 62ms | 6.83
| TeamStore.GetTeamsForUser | p99 | 382ms | 408ms | 26ms | 6.81
| ThreadStore.GetTotalThreads | p99 | 460ms | 489ms | 29ms | 6.31
| PostPriorityStore.GetForPosts | p99 | 918ms | 973ms | 55ms | 5.99
| StatusStore.SaveOrUpdate | p99 | 912ms | 966ms | 54ms | 5.92
| ChannelStore.GetFileCount | p99 | 427ms | 452ms | 25ms | 5.86
| ThreadStore.GetTotalUnreadThreads | p99 | 461ms | 488ms | 27ms | 5.85
| PostStore.Get | p99 | 942ms | 997ms | 55ms | 5.84
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 465ms | 490ms | 25ms | 5.38
| ChannelStore.GetAllChannelMembersForUser | p99 | 398ms | 418ms | 20ms | 5.03
| TeamStore.GetTeamsByUserId | p99 | 474ms | 497ms | 23ms | 4.85
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 466ms | 488ms | 22ms | 4.72
| ThreadStore.GetThreadForUser | p99 | 877ms | 916ms | 39ms | 4.45
| PostStore.GetPostIdAfterTime | p99 | 45ms | 47ms | 2ms | 4.44
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 465ms | 485ms | 20ms | 4.30
| ThreadStore.GetTotalUnreadMentions | p99 | 465ms | 485ms | 20ms | 4.30
| ThreadStore.MarkAsRead | p99 | 47ms | 49ms | 2ms | 4.22
| UserStore.GetForLogin | p99 | 432ms | 450ms | 18ms | 4.17
| GroupStore.GetByName | p99 | 419ms | 436ms | 17ms | 4.06
| FileInfoStore.Get | p99 | 458ms | 476ms | 18ms | 3.93
| UserStore.GetAllProfiles | p99 | 440ms | 457ms | 17ms | 3.86
| UserStore.GetProfilesByUsernames | p99 | 469ms | 487ms | 18ms | 3.84
| ChannelStore.GetMemberLastViewedAt | p99 | 451ms | 468ms | 17ms | 3.77
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 480ms | 498ms | 18ms | 3.75
| UserStore.GetUnreadCount | p99 | 457ms | 474ms | 17ms | 3.72
| TeamStore.GetAllPage | p99 | 471ms | 486ms | 15ms | 3.19
| ChannelStore.GetMemberCount | p99 | 1.439s | 1.484s | 45ms | 3.13
| SessionStore.GetLRUSessions | p99 | 428ms | 439ms | 11ms | 2.57
| SessionStore.Get | p99 | 484ms | 496ms | 12ms | 2.48
| PostStore.GetPostReminderMetadata | p99 | 455ms | 466ms | 11ms | 2.42
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 499ms | 511ms | 12ms | 2.40
| UserTermsOfServiceStore.GetByUser | p99 | 474ms | 485ms | 11ms | 2.32
| PostStore.GetPosts | p99 | 448ms | 458ms | 10ms | 2.23
| StatusStore.Get | p99 | 414ms | 423ms | 9ms | 2.18
| ChannelStore.SaveMember | p99 | 2.244s | 2.292s | 48ms | 2.14
| ThreadStore.MaintainMembership | p99 | 96ms | 98ms | 2ms | 2.07
| UserStore.Search | p99 | 962ms | 977ms | 15ms | 1.56
| UserStore.GetProfileByIds | p99 | 457ms | 464ms | 7ms | 1.53
| ChannelStore.GetByName | p99 | 492ms | 499ms | 7ms | 1.42
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.GetPostsByIds | avg | 31ms | 0s | -31ms | -101.28
| TeamStore.GetMany | avg | 83ms | 0s | -83ms | -99.89
| ChannelStore.GetChannelsByIds | avg | 25ms | 0s | -25ms | -98.97
| BotStore.Save | avg | 10ms | 0s | -10ms | -98.24
| EmojiStore.GetMultipleByName | avg | 66ms | 5ms | -61ms | -92.78
| PostPersistentNotificationStore.UpdateLastActivity | avg | 2ms | 0s | -2ms | -84.66
| PostStore.Delete | avg | 124ms | 56ms | -68ms | -54.99
| PostStore.AnalyticsPostCount | avg | 2.788s | 1.309s | -1.479s | -53.05
| RoleStore.ChannelHigherScopedPermissions | avg | 40ms | 21ms | -19ms | -47.13
| ChannelStore.GetSidebarCategory | avg | 87ms | 56ms | -31ms | -35.70
| SessionStore.Remove | avg | 8ms | 6ms | -2ms | -26.36
| PostStore.Update | avg | 24ms | 19ms | -5ms | -21.10
| ChannelStore.GetTeamChannels | avg | 99ms | 85ms | -14ms | -14.21
| ChannelStore.GetPublicChannelsForTeam | avg | 86ms | 78ms | -8ms | -9.25
| ChannelStore.GetMemberCount | avg | 349ms | 343ms | -6ms | -1.72
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -100.96
| BotStore.Save | p99 | 25ms | 0s | -25ms | -100.60
| ChannelStore.GetChannelsByIds | p99 | 243ms | 0s | -243ms | -100.20
| TeamStore.GetMany | p99 | 488ms | 0s | -488ms | -100.10
| PostStore.GetPostsByIds | p99 | 244ms | 0s | -244ms | -100.00
| EmojiStore.GetMultipleByName | p99 | 242ms | 24ms | -218ms | -90.18
| PostPersistentNotificationStore.Get | p99 | 37ms | 9ms | -28ms | -75.16
| JobStore.UpdateStatus | p99 | 62ms | 22ms | -40ms | -64.52
| PostStore.Update | p99 | 232ms | 95ms | -137ms | -59.05
| ThreadStore.MarkAllAsReadByTeam | p99 | 10ms | 5ms | -5ms | -51.28
| SessionStore.Remove | p99 | 90ms | 44ms | -46ms | -50.83
| PostStore.Delete | p99 | 487ms | 243ms | -244ms | -50.05
| ChannelStore.UpdateSidebarCategories | p99 | 1.81s | 905ms | -905ms | -50.00
| ChannelStore.GetTeamChannels | p99 | 472ms | 247ms | -225ms | -47.62
| SessionStore.GetSessionsExpired | p99 | 472ms | 247ms | -225ms | -47.62
| ChannelStore.CreateDirectChannel | p99 | 1.828s | 970ms | -858ms | -46.95
| UserStore.Update | p99 | 150ms | 81ms | -69ms | -45.92
| ChannelStore.GetSidebarCategory | p99 | 1.12s | 640ms | -480ms | -42.86
| PluginStore.List | p99 | 720ms | 469ms | -251ms | -34.86
| UserStore.Count | p99 | 2.275s | 1.705s | -570ms | -25.05
| PostPriorityStore.GetForPost | p99 | 900ms | 705ms | -195ms | -21.67
| PluginStore.SetWithOptions | p99 | 60ms | 49ms | -11ms | -18.33
| JobStore.GetCountByStatusAndType | p99 | 610ms | 500ms | -110ms | -18.03
| PostPersistentNotificationStore.DeleteExpired | p99 | 23ms | 19ms | -4ms | -17.58
| ChannelStore.GetPinnedPostCount | p99 | 599ms | 499ms | -100ms | -16.68
| ClusterDiscoveryStore.SetLastPingAt | p99 | 44ms | 37ms | -7ms | -16.07
| FileInfoStore.Save | p99 | 57ms | 48ms | -9ms | -15.71
| PreferenceStore.Save | p99 | 149ms | 128ms | -21ms | -14.10
| ChannelStore.GetPublicChannelsForTeam | p99 | 843ms | 725ms | -118ms | -13.99
| StatusStore.GetByIds | p99 | 574ms | 496ms | -78ms | -13.59
| FileInfoStore.SetContent | p99 | 82ms | 71ms | -11ms | -13.49
| UserStore.UpdateLastLogin | p99 | 41ms | 37ms | -4ms | -9.74
| ProductNoticesStore.View | p99 | 323ms | 293ms | -30ms | -9.29
| FileInfoStore.AttachToPost | p99 | 49ms | 46ms | -3ms | -6.10
| UserStore.UpdateFailedPasswordAttempts | p99 | 47ms | 45ms | -2ms | -4.23
| AuditStore.Save | p99 | 48ms | 46ms | -2ms | -4.18
| UserStore.Save | p99 | 241ms | 235ms | -6ms | -2.49
| FileInfoStore.GetForPost | p99 | 704ms | 689ms | -15ms | -2.13
| PostStore.GetPostsAfter | p99 | 486ms | 478ms | -8ms | -1.64
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 39ms | 333ms | 294ms | 758.07
| getChannelMembers | avg | 4ms | 26ms | 22ms | 616.17
| followThreadByUser | avg | 77ms | 122ms | 45ms | 58.62
| unfollowThreadByUser | avg | 124ms | 196ms | 72ms | 58.07
| patchPost | avg | 1.167s | 1.787s | 620ms | 53.15
| searchPostsInTeam | avg | 237ms | 338ms | 101ms | 42.59
| getChannelsForUser | avg | 36ms | 51ms | 15ms | 41.41
| createGroupChannel | avg | 814ms | 1.125s | 311ms | 38.21
| getTeamMember | avg | 5ms | 7ms | 2ms | 37.25
| getChannelUnread | avg | 32ms | 42ms | 10ms | 31.62
| getPostsForChannel | avg | 400ms | 502ms | 102ms | 25.48
| updateReadStateThreadByUser | avg | 407ms | 498ms | 91ms | 22.39
| autocompleteChannelsForTeamForSearch | avg | 262ms | 319ms | 57ms | 21.74
| getChannelMembersForTeamForUser | avg | 48ms | 58ms | 10ms | 20.64
| getChannelsForTeamForUser | avg | 50ms | 60ms | 10ms | 19.99
| saveReaction | avg | 162ms | 194ms | 32ms | 19.73
| getThreadsForUser | avg | 56ms | 67ms | 11ms | 19.57
| getPostThread | avg | 311ms | 365ms | 54ms | 17.37
| getTeamStats | avg | 369ms | 433ms | 64ms | 17.32
| getUsersByNames | avg | 40ms | 47ms | 7ms | 17.31
| viewChannel | avg | 104ms | 122ms | 18ms | 17.26
| getTeamMembersForUser | avg | 31ms | 36ms | 5ms | 16.33
| searchGroupChannels | avg | 60ms | 69ms | 9ms | 14.91
| createChannel | avg | 725ms | 833ms | 108ms | 14.90
| getCategoriesForTeamForUser | avg | 101ms | 116ms | 15ms | 14.78
| getTeamsUnreadForUser | avg | 68ms | 77ms | 9ms | 13.16
| getPostsForChannelAroundLastUnread | avg | 198ms | 224ms | 26ms | 13.10
| getChannelMember | avg | 53ms | 60ms | 7ms | 13.09
| createPost | avg | 1.323s | 1.487s | 164ms | 12.40
| getTeamsForUser | avg | 47ms | 52ms | 5ms | 10.75
| getAllTeams | avg | 47ms | 52ms | 5ms | 10.72
| addChannelMember | avg | 855ms | 945ms | 90ms | 10.52
| searchUsers | avg | 204ms | 225ms | 21ms | 10.30
| getUser | avg | 63ms | 69ms | 6ms | 9.56
| getChannel | avg | 96ms | 105ms | 9ms | 9.34
| getUsers | avg | 33ms | 36ms | 3ms | 9.05
| getFileThumbnail | avg | 70ms | 76ms | 6ms | 8.54
| autocompleteUsers | avg | 338ms | 366ms | 28ms | 8.29
| getPreferences | avg | 61ms | 66ms | 5ms | 8.22
| searchAllChannels | avg | 2.258s | 2.388s | 130ms | 5.76
| getFilePreview | avg | 76ms | 80ms | 4ms | 5.28
| login | avg | 198ms | 207ms | 9ms | 4.55
| getChannelStats | avg | 53ms | 55ms | 2ms | 3.79
| createDirectChannel | avg | 457ms | 469ms | 12ms | 2.62
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 99ms | 2.38s | 2.281s | 2315.09
| getChannelMembers | p99 | 5ms | 50ms | 45ms | 909.09
| unfollowThreadByUser | p99 | 914ms | 2.213s | 1.299s | 142.19
| followThreadByUser | p99 | 475ms | 950ms | 475ms | 100.00
| createChannel | p99 | 2.445s | 4.725s | 2.28s | 93.25
| createGroupChannel | p99 | 4.887s | 7.783s | 2.896s | 59.25
| patchPost | p99 | 6.55s | 10s | 3.45s | 52.67
| searchPostsInTeam | p99 | 2.909s | 4.264s | 1.355s | 46.58
| getChannel | p99 | 981ms | 1.37s | 389ms | 39.65
| getChannelsForTeamForUser | p99 | 500ms | 687ms | 187ms | 37.42
| getPostsForChannel | p99 | 5.695s | 7.485s | 1.79s | 31.43
| viewChannel | p99 | 1.089s | 1.427s | 338ms | 31.03
| getPostThread | p99 | 2.803s | 3.595s | 792ms | 28.26
| getCategoriesForTeamForUser | p99 | 981ms | 1.234s | 253ms | 25.78
| getChannelMembersForTeamForUser | p99 | 489ms | 604ms | 115ms | 23.52
| getThreadsForUser | p99 | 679ms | 801ms | 122ms | 17.97
| autocompleteChannelsForTeamForSearch | p99 | 1.975s | 2.327s | 352ms | 17.82
| getPreferences | p99 | 578ms | 660ms | 82ms | 14.18
| getChannelUnread | p99 | 417ms | 473ms | 56ms | 13.43
| saveReaction | p99 | 1.936s | 2.187s | 251ms | 12.96
| createPost | p99 | 8.046s | 8.963s | 917ms | 11.40
| getUsersByIds | p99 | 100ms | 111ms | 11ms | 11.02
| autocompleteUsers | p99 | 1.786s | 1.982s | 196ms | 10.97
| getChannelsForUser | p99 | 435ms | 482ms | 47ms | 10.80
| getUser | p99 | 734ms | 808ms | 74ms | 10.09
| getChannelMember | p99 | 761ms | 836ms | 75ms | 9.86
| updateReadStateThreadByUser | p99 | 4.042s | 4.42s | 378ms | 9.35
| getTeamMembersForUser | p99 | 412ms | 439ms | 27ms | 6.55
| getTeamsUnreadForUser | p99 | 870ms | 922ms | 52ms | 5.98
| login | p99 | 1.952s | 2.056s | 104ms | 5.33
| getTeamsForUser | p99 | 474ms | 498ms | 24ms | 5.06
| getPostsForChannelAroundLastUnread | p99 | 2.337s | 2.448s | 111ms | 4.75
| getUsers | p99 | 470ms | 491ms | 21ms | 4.46
| getUsersByNames | p99 | 472ms | 490ms | 18ms | 3.81
| getClientConfig | p99 | 230ms | 237ms | 7ms | 3.04
| getFileThumbnail | p99 | 485ms | 499ms | 14ms | 2.89
| getAllTeams | p99 | 484ms | 496ms | 12ms | 2.48
| getFilePreview | p99 | 481ms | 492ms | 11ms | 2.29
| getChannelStats | p99 | 937ms | 951ms | 14ms | 1.49
| searchUsers | p99 | 963ms | 977ms | 14ms | 1.45
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deletePost | avg | 605ms | 182ms | -423ms | -69.87
| setPostReminder | avg | 312ms | 250ms | -62ms | -19.87
| updateCategoriesForTeamForUser | avg | 372ms | 321ms | -51ms | -13.71
| logout | avg | 219ms | 194ms | -25ms | -11.40
| getPublicChannelsForTeam | avg | 88ms | 79ms | -9ms | -10.22
| removeUserCustomStatus | avg | 188ms | 182ms | -6ms | -3.20
| getProfileImage | avg | 96ms | 93ms | -3ms | -3.12
| uploadFileStream | avg | 431ms | 426ms | -5ms | -1.16
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deletePost | p99 | 4.5s | 965ms | -3.535s | -78.56
| logout | p99 | 2.215s | 960ms | -1.255s | -56.66
| setPostReminder | p99 | 2.215s | 980ms | -1.235s | -55.76
| updateReadStateAllThreadsByUser | p99 | 10ms | 5ms | -5ms | -51.28
| createDirectChannel | p99 | 3.745s | 2.414s | -1.331s | -35.54
| addChannelMember | p99 | 6.5s | 4.959s | -1.541s | -23.71
| createUser | p99 | 1.536s | 1.201s | -335ms | -21.81
| getTeamMember | p99 | 121ms | 98ms | -23ms | -19.05
| getPublicChannelsForTeam | p99 | 843ms | 725ms | -118ms | -13.99
| removeUserCustomStatus | p99 | 890ms | 818ms | -72ms | -8.09
| updateCategoriesForTeamForUser | p99 | 2.401s | 2.215s | -186ms | -7.75
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 48ms| 46ms | -2ms | -4.178
| BotStore.Get |  Avg| 17ms| 46ms | 29ms | 171.638
| |  P99| 208ms| 422ms | 214ms | 102.885
| BotStore.Save |  Avg| 10ms| 0s | -10ms | -98.238
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 5ms | 1ms | 22.507
| |  P99| 46ms| 47ms | 1ms | 2.187
| ChannelStore.Autocomplete |  Avg| 2.257s| 2.386s | 129ms | 5.715
| |  P99| 9.453s| 9.524s | 71ms | 0.751
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 262ms| 319ms | 57ms | 21.742
| |  P99| 1.975s| 2.327s | 352ms | 17.823
| ChannelStore.CreateDirectChannel |  Avg| 143ms| 166ms | 23ms | 16.099
| |  P99| 1.828s| 970ms | -858ms | -46.948
| ChannelStore.CreateInitialSidebarCategories |  Avg| 63ms| 66ms | 3ms | 4.736
| |  P99| 495ms| 549ms | 54ms | 10.905
| ChannelStore.CreateSidebarCategory |  Avg| 25ms| 50ms | 25ms | 98.182
| |  P99| 98ms| 480ms | 382ms | 387.818
| ChannelStore.Get |  Avg| 93ms| 105ms | 12ms | 12.881
| |  P99| 831ms| 894ms | 63ms | 7.583
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 59ms| 83ms | 24ms | 40.543
| |  P99| 496ms| 669ms | 173ms | 34.914
| ChannelStore.GetAllChannelMembersForUser |  Avg| 32ms| 36ms | 4ms | 12.583
| |  P99| 398ms| 418ms | 20ms | 5.029
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 65ms| 68ms | 3ms | 4.620
| |  P99| 492ms| 489ms | -3ms | -0.610
| ChannelStore.GetByName |  Avg| 51ms| 53ms | 2ms | 3.956
| |  P99| 492ms| 499ms | 7ms | 1.423
| ChannelStore.GetChannelUnread |  Avg| 29ms| 39ms | 10ms | 35.013
| |  P99| 370ms| 454ms | 84ms | 22.706
| ChannelStore.GetChannels |  Avg| 49ms| 59ms | 10ms | 20.537
| |  P99| 493ms| 651ms | 158ms | 32.023
| ChannelStore.GetChannelsByIds |  Avg| 25ms| 0s | -25ms | -98.969
| |  P99| 243ms| 0s | -243ms | -100.203
| ChannelStore.GetChannelsByUser |  Avg| 36ms| 50ms | 14ms | 38.731
| |  P99| 435ms| 483ms | 48ms | 11.033
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 43ms| 50ms | 7ms | 16.382
| |  P99| 480ms| 498ms | 18ms | 3.752
| ChannelStore.GetFileCount |  Avg| 36ms| 40ms | 4ms | 11.000
| |  P99| 427ms| 452ms | 25ms | 5.857
| ChannelStore.GetGuestCount |  Avg| 69ms| 76ms | 7ms | 10.102
| |  P99| 656ms| 768ms | 112ms | 17.077
| ChannelStore.GetMember |  Avg| 4ms| 5ms | 1ms | 22.704
| |  P99| 79ms| 90ms | 11ms | 13.936
| ChannelStore.GetMemberCount |  Avg| 349ms| 343ms | -6ms | -1.717
| |  P99| 1.439s| 1.484s | 45ms | 3.126
| ChannelStore.GetMemberForPost |  Avg| 60ms| 73ms | 13ms | 21.622
| |  P99| 634ms| 790ms | 156ms | 24.610
| ChannelStore.GetMemberLastViewedAt |  Avg| 36ms| 40ms | 4ms | 10.975
| |  P99| 451ms| 468ms | 17ms | 3.769
| ChannelStore.GetMembers |  Avg| 3ms| 26ms | 23ms | 778.875
| |  P99| 5ms| 50ms | 45ms | 909.091
| ChannelStore.GetMembersForUser |  Avg| 48ms| 58ms | 10ms | 20.898
| |  P99| 486ms| 594ms | 108ms | 22.213
| ChannelStore.GetPinnedPostCount |  Avg| 51ms| 58ms | 7ms | 13.620
| |  P99| 599ms| 499ms | -100ms | -16.683
| ChannelStore.GetPublicChannelsForTeam |  Avg| 86ms| 78ms | -8ms | -9.250
| |  P99| 843ms| 725ms | -118ms | -13.992
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 101ms| 116ms | 15ms | 14.840
| |  P99| 980ms| 1.234s | 254ms | 25.922
| ChannelStore.GetSidebarCategory |  Avg| 87ms| 56ms | -31ms | -35.699
| |  P99| 1.12s| 640ms | -480ms | -42.855
| ChannelStore.GetTeamChannels |  Avg| 99ms| 85ms | -14ms | -14.208
| |  P99| 472ms| 247ms | -225ms | -47.620
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 44ms | 0s | 0.000
| ChannelStore.Save |  Avg| 50ms| 93ms | 43ms | 85.336
| |  P99| 325ms| 885ms | 560ms | 172.317
| ChannelStore.SaveMember |  Avg| 227ms| 239ms | 12ms | 5.293
| |  P99| 2.244s| 2.292s | 48ms | 2.139
| ChannelStore.SearchGroupChannels |  Avg| 60ms| 69ms | 9ms | 14.926
| |  P99| 771ms| 767ms | -4ms | -0.519
| ChannelStore.UpdateLastViewedAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 89ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 137ms| 151ms | 14ms | 10.242
| |  P99| 1.81s| 905ms | -905ms | -49.999
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 38ms| 41ms | 3ms | 7.951
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 4ms | -1ms | -20.991
| |  P99| 44ms| 37ms | -7ms | -16.066
| CommandWebhookStore.Cleanup |  Avg| 1ms| 17ms | 16ms | 2306.744
| |  P99| 5ms| 98ms | 93ms | 1878.788
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 8ms | 4ms | 105.687
| |  P99| 24ms| 93ms | 69ms | 287.500
| EmojiStore.GetByName |  Avg| 51ms| 59ms | 8ms | 15.703
| |  P99| 499ms| 642ms | 143ms | 28.680
| EmojiStore.GetMultipleByName |  Avg| 66ms| 5ms | -61ms | -92.778
| |  P99| 242ms| 24ms | -218ms | -90.176
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 49ms| 46ms | -3ms | -6.098
| FileInfoStore.Get |  Avg| 37ms| 42ms | 5ms | 13.535
| |  P99| 458ms| 476ms | 18ms | 3.933
| FileInfoStore.GetForPost |  Avg| 62ms| 63ms | 1ms | 1.616
| |  P99| 704ms| 689ms | -15ms | -2.131
| FileInfoStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 57ms| 48ms | -9ms | -15.713
| FileInfoStore.SetContent |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 82ms| 71ms | -11ms | -13.489
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 52ms| 54ms | 2ms | 3.862
| |  P99| 499ms| 511ms | 12ms | 2.403
| GroupStore.GetByName |  Avg| 33ms| 35ms | 2ms | 5.976
| |  P99| 419ms| 436ms | 17ms | 4.059
| GroupStore.GetGroups |  Avg| 53ms| 62ms | 9ms | 17.116
| |  P99| 526ms| 675ms | 149ms | 28.339
| JobStore.Get |  Avg| 47ms| 73ms | 26ms | 54.786
| |  P99| 620ms| 851ms | 231ms | 37.257
| JobStore.GetAllByStatus |  Avg| 50ms| 55ms | 5ms | 9.999
| |  P99| 494ms| 550ms | 56ms | 11.336
| JobStore.GetCountByStatusAndType |  Avg| 51ms| 76ms | 25ms | 48.646
| |  P99| 610ms| 500ms | -110ms | -18.033
| JobStore.GetNewestJobByStatusesAndType |  Avg| 53ms| 72ms | 19ms | 35.838
| |  P99| 610ms| 717ms | 107ms | 17.541
| JobStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 40ms| 67ms | 27ms | 66.667
| JobStore.UpdateOptimistically |  Avg| 4ms| 6ms | 2ms | 49.578
| |  P99| 31ms| 55ms | 24ms | 77.416
| JobStore.UpdateStatus |  Avg| 5ms| 4ms | -1ms | -21.429
| |  P99| 62ms| 22ms | -40ms | -64.524
| JobStore.UpdateStatusOptimistically |  Avg| 6ms| 5ms | -1ms | -15.476
| |  P99| 46ms| 67ms | 21ms | 45.455
| LinkMetadataStore.Get |  Avg| 49ms| 60ms | 11ms | 22.395
| |  P99| 499ms| 672ms | 173ms | 34.636
| LinkMetadataStore.Save |  Avg| 3ms| 2ms | -1ms | -38.674
| |  P99| 9ms| 40ms | 31ms | 353.165
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.221
| PluginStore.List |  Avg| 67ms| 84ms | 17ms | 25.471
| |  P99| 720ms| 469ms | -251ms | -34.861
| PluginStore.SetWithOptions |  Avg| 6ms| 5ms | -1ms | -17.610
| |  P99| 60ms| 49ms | -11ms | -18.332
| PostAcknowledgementStore.GetForPost |  Avg| 46ms| 63ms | 17ms | 37.165
| |  P99| 495ms| 823ms | 328ms | 66.207
| PostAcknowledgementStore.GetForPosts |  Avg| 65ms| 76ms | 11ms | 16.980
| |  P99| 908ms| 970ms | 62ms | 6.826
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 23ms| 19ms | -4ms | -17.582
| PostPersistentNotificationStore.Get |  Avg| 2ms| 1ms | -1ms | -50.435
| |  P99| 37ms| 9ms | -28ms | -75.156
| PostPersistentNotificationStore.GetSingle |  Avg| 51ms| 61ms | 10ms | 19.772
| |  P99| 528ms| 635ms | 107ms | 20.279
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 2ms| 0s | -2ms | -84.663
| |  P99| 5ms| 0s | -5ms | -100.960
| PostPriorityStore.GetForPost |  Avg| 60ms| 60ms | 0s | 0.000
| |  P99| 900ms| 705ms | -195ms | -21.668
| PostPriorityStore.GetForPosts |  Avg| 67ms| 78ms | 11ms | 16.477
| |  P99| 918ms| 973ms | 55ms | 5.991
| PostStore.AnalyticsPostCount |  Avg| 2.788s| 1.309s | -1.479s | -53.048
| |  P99| 4.975s| 4.95s | -25ms | -0.503
| PostStore.Delete |  Avg| 124ms| 56ms | -68ms | -54.987
| |  P99| 487ms| 243ms | -244ms | -50.051
| PostStore.Get |  Avg| 87ms| 108ms | 21ms | 24.072
| |  P99| 942ms| 997ms | 55ms | 5.837
| PostStore.GetEtag |  Avg| 66ms| 74ms | 8ms | 12.095
| |  P99| 667ms| 767ms | 100ms | 14.997
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 47ms | 2ms | 4.436
| PostStore.GetPostIdBeforeTime |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 48ms| 49ms | 1ms | 2.076
| PostStore.GetPostReminderMetadata |  Avg| 42ms| 54ms | 12ms | 28.290
| |  P99| 455ms| 466ms | 11ms | 2.418
| PostStore.GetPostReminders |  Avg| 4ms| 8ms | 4ms | 94.932
| |  P99| 23ms| 94ms | 71ms | 310.044
| PostStore.GetPosts |  Avg| 38ms| 40ms | 2ms | 5.296
| |  P99| 448ms| 458ms | 10ms | 2.233
| PostStore.GetPostsAfter |  Avg| 41ms| 52ms | 11ms | 27.052
| |  P99| 486ms| 478ms | -8ms | -1.645
| PostStore.GetPostsBefore |  Avg| 51ms| 60ms | 9ms | 17.517
| |  P99| 497ms| 627ms | 130ms | 26.133
| PostStore.GetPostsByIds |  Avg| 31ms| 0s | -31ms | -101.284
| |  P99| 244ms| 0s | -244ms | -99.998
| PostStore.GetPostsByThread |  Avg| 50ms| 67ms | 17ms | 33.752
| |  P99| 498ms| 747ms | 249ms | 50.035
| PostStore.GetPostsSince |  Avg| 70ms| 81ms | 11ms | 15.760
| |  P99| 603ms| 744ms | 141ms | 23.365
| PostStore.GetSingle |  Avg| 48ms| 59ms | 11ms | 22.881
| |  P99| 496ms| 664ms | 168ms | 33.898
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 166ms| 167ms | 1ms | 0.603
| PostStore.SearchPostsForUser |  Avg| 138ms| 186ms | 48ms | 34.813
| |  P99| 1.066s| 1.529s | 463ms | 43.419
| PostStore.SetPostReminder |  Avg| 5ms| 9ms | 4ms | 73.011
| |  P99| 24ms| 93ms | 69ms | 292.681
| PostStore.Update |  Avg| 24ms| 19ms | -5ms | -21.096
| |  P99| 232ms| 95ms | -137ms | -59.051
| PreferenceStore.DeleteCategoryAndName |  Avg| 4ms| 9ms | 5ms | 137.418
| |  P99| 23ms| 93ms | 70ms | 297.873
| PreferenceStore.Get |  Avg| 46ms| 54ms | 8ms | 17.486
| |  P99| 492ms| 601ms | 109ms | 22.144
| PreferenceStore.GetAll |  Avg| 59ms| 64ms | 5ms | 8.432
| |  P99| 529ms| 612ms | 83ms | 15.700
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 149ms| 128ms | -21ms | -14.100
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 34ms| 33ms | -1ms | -2.951
| |  P99| 323ms| 293ms | -30ms | -9.287
| ReactionStore.GetForPost |  Avg| 53ms| 67ms | 14ms | 26.219
| |  P99| 626ms| 720ms | 94ms | 15.018
| RoleStore.ChannelHigherScopedPermissions |  Avg| 40ms| 21ms | -19ms | -47.126
| |  P99| 180ms| 333ms | 153ms | 84.882
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 48ms| 51ms | 3ms | 6.253
| |  P99| 484ms| 496ms | 12ms | 2.482
| SessionStore.GetLRUSessions |  Avg| 32ms| 36ms | 4ms | 12.607
| |  P99| 428ms| 439ms | 11ms | 2.569
| SessionStore.GetSessionsExpired |  Avg| 60ms| 76ms | 16ms | 26.723
| |  P99| 472ms| 247ms | -225ms | -47.619
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 38ms| 45ms | 7ms | 18.557
| |  P99| 465ms| 485ms | 20ms | 4.302
| SessionStore.Remove |  Avg| 8ms| 6ms | -2ms | -26.358
| |  P99| 90ms| 44ms | -46ms | -50.829
| SessionStore.Save |  Avg| 34ms| 40ms | 6ms | 17.459
| |  P99| 414ms| 446ms | 32ms | 7.735
| SessionStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| StatusStore.Get |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 414ms| 423ms | 9ms | 2.176
| StatusStore.GetByIds |  Avg| 58ms| 69ms | 11ms | 18.994
| |  P99| 574ms| 496ms | -78ms | -13.589
| StatusStore.SaveOrUpdate |  Avg| 61ms| 77ms | 16ms | 26.129
| |  P99| 912ms| 966ms | 54ms | 5.924
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 5ms | 2ms | 57.818
| |  P99| 43ms| 86ms | 43ms | 100.000
| StatusStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 40ms| 39ms | -1ms | -2.523
| TeamStore.Get |  Avg| 48ms| 58ms | 10ms | 21.039
| |  P99| 495ms| 639ms | 144ms | 29.068
| TeamStore.GetActiveMemberCount |  Avg| 367ms| 422ms | 55ms | 14.998
| |  P99| 982ms| 986ms | 4ms | 0.407
| TeamStore.GetAllPage |  Avg| 44ms| 49ms | 5ms | 11.441
| |  P99| 471ms| 486ms | 15ms | 3.185
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 42ms| 48ms | 6ms | 14.163
| |  P99| 466ms| 488ms | 22ms | 4.717
| TeamStore.GetMany |  Avg| 83ms| 0s | -83ms | -99.894
| |  P99| 488ms| 0s | -488ms | -100.102
| TeamStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 48ms| 54ms | 6ms | 12.392
| TeamStore.GetTeamsByUserId |  Avg| 46ms| 52ms | 6ms | 12.930
| |  P99| 474ms| 497ms | 23ms | 4.854
| TeamStore.GetTeamsForUser |  Avg| 28ms| 33ms | 5ms | 17.798
| |  P99| 382ms| 408ms | 26ms | 6.815
| TeamStore.GetTotalMemberCount |  Avg| 283ms| 363ms | 80ms | 28.307
| |  P99| 496ms| 945ms | 449ms | 90.511
| TeamStore.SaveMember |  Avg| 154ms| 155ms | 1ms | 0.651
| |  P99| 666ms| 748ms | 82ms | 12.304
| ThreadStore.Get |  Avg| 49ms| 89ms | 40ms | 82.366
| |  P99| 434ms| 954ms | 520ms | 119.954
| ThreadStore.GetMembershipForUser |  Avg| 47ms| 56ms | 9ms | 19.271
| |  P99| 489ms| 568ms | 79ms | 16.164
| ThreadStore.GetTeamsUnreadForUser |  Avg| 49ms| 55ms | 6ms | 12.250
| |  P99| 628ms| 763ms | 135ms | 21.513
| ThreadStore.GetThreadFollowers |  Avg| 51ms| 64ms | 13ms | 25.333
| |  P99| 602ms| 726ms | 124ms | 20.606
| ThreadStore.GetThreadForUser |  Avg| 69ms| 85ms | 16ms | 23.053
| |  P99| 877ms| 916ms | 39ms | 4.447
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 57ms| 68ms | 11ms | 19.166
| |  P99| 637ms| 754ms | 117ms | 18.362
| ThreadStore.GetThreadsForUser |  Avg| 57ms| 68ms | 11ms | 19.377
| |  P99| 614ms| 738ms | 124ms | 20.182
| ThreadStore.GetTotalThreads |  Avg| 39ms| 46ms | 7ms | 18.040
| |  P99| 460ms| 489ms | 29ms | 6.305
| ThreadStore.GetTotalUnreadMentions |  Avg| 39ms| 45ms | 6ms | 15.317
| |  P99| 465ms| 485ms | 20ms | 4.298
| ThreadStore.GetTotalUnreadThreads |  Avg| 38ms| 45ms | 7ms | 18.262
| |  P99| 461ms| 488ms | 27ms | 5.851
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 39ms| 45ms | 6ms | 15.298
| |  P99| 465ms| 490ms | 25ms | 5.378
| ThreadStore.MaintainMembership |  Avg| 7ms| 8ms | 1ms | 13.752
| |  P99| 96ms| 98ms | 2ms | 2.074
| ThreadStore.MarkAllAsReadByChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 63ms| 62ms | -1ms | -1.595
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.282
| ThreadStore.MarkAsRead |  Avg| 5ms| 6ms | 1ms | 18.566
| |  P99| 47ms| 49ms | 2ms | 4.216
| ThreadStore.UpdateMembership |  Avg| 5ms| 6ms | 1ms | 18.239
| |  P99| 62ms| 62ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 5ms | 4ms | 590.455
| |  P99| 5ms| 10ms | 5ms | 101.010
| UserAccessTokenStore.GetByToken |  Avg| 36ms| 45ms | 9ms | 24.803
| |  P99| 413ms| 467ms | 54ms | 13.091
| UserStore.AutocompleteUsersInChannel |  Avg| 415ms| 459ms | 44ms | 10.605
| |  P99| 1.948s| 2.129s | 181ms | 9.292
| UserStore.Count |  Avg| 274ms| 306ms | 32ms | 11.697
| |  P99| 2.275s| 1.705s | -570ms | -25.055
| UserStore.Get |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 359ms| 357ms | -2ms | -0.557
| UserStore.GetAllProfiles |  Avg| 36ms| 39ms | 3ms | 8.308
| |  P99| 440ms| 457ms | 17ms | 3.860
| UserStore.GetAllProfilesInChannel |  Avg| 852ms| 846ms | -6ms | -0.705
| |  P99| 2.466s| 2.466s | 0s | 0.000
| UserStore.GetByUsername |  Avg| 47ms| 73ms | 26ms | 55.780
| |  P99| 494ms| 494ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 34ms| 37ms | 3ms | 8.801
| |  P99| 432ms| 450ms | 18ms | 4.170
| UserStore.GetMany |  Avg| 12ms| 74ms | 62ms | 531.824
| |  P99| 214ms| 457ms | 243ms | 113.553
| UserStore.GetProfileByIds |  Avg| 30ms| 33ms | 3ms | 10.127
| |  P99| 457ms| 464ms | 7ms | 1.533
| UserStore.GetProfilesByUsernames |  Avg| 40ms| 46ms | 6ms | 15.066
| |  P99| 469ms| 487ms | 18ms | 3.840
| UserStore.GetProfilesInChannel |  Avg| 45ms| 156ms | 111ms | 248.275
| |  P99| 457ms| 1.45s | 993ms | 217.055
| UserStore.GetProfilesNotInChannel |  Avg| 67ms| 151ms | 84ms | 124.579
| |  P99| 245ms| 945ms | 700ms | 286.298
| UserStore.GetUnreadCount |  Avg| 38ms| 48ms | 10ms | 26.314
| |  P99| 457ms| 474ms | 17ms | 3.719
| UserStore.IsEmpty |  Avg| 22ms| 23ms | 1ms | 4.514
| |  P99| 286ms| 312ms | 26ms | 9.079
| UserStore.Save |  Avg| 75ms| 74ms | -1ms | -1.338
| |  P99| 241ms| 235ms | -6ms | -2.487
| UserStore.Search |  Avg| 203ms| 223ms | 20ms | 9.860
| |  P99| 962ms| 977ms | 15ms | 1.559
| UserStore.Update |  Avg| 9ms| 8ms | -1ms | -10.837
| |  P99| 150ms| 81ms | -69ms | -45.924
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 47ms| 45ms | -2ms | -4.235
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 37ms | -4ms | -9.735
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 47ms| 46ms | -1ms | -2.130
| UserTermsOfServiceStore.GetByUser |  Avg| 43ms| 48ms | 5ms | 11.531
| |  P99| 474ms| 485ms | 11ms | 2.320
| WebhookStore.GetOutgoingByTeam |  Avg| 55ms| 65ms | 10ms | 18.066
| |  P99| 608ms| 718ms | 110ms | 18.087
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 855ms| 945ms | 90ms | 10.525
| | P99| 6.5s| 4.959s | -1.541s | -23.708
| addTeamMember | Avg| 2.531s| 2.532s | 1ms | 0.040
| | P99| 10s| 9.976s | -24ms | -0.240
| autocompleteChannelsForTeamForSearch | Avg| 262ms| 319ms | 57ms | 21.737
| | P99| 1.975s| 2.327s | 352ms | 17.823
| autocompleteUsers | Avg| 338ms| 366ms | 28ms | 8.286
| | P99| 1.786s| 1.982s | 196ms | 10.974
| createCategoryForTeamForUser | Avg| 39ms| 333ms | 294ms | 758.067
| | P99| 99ms| 2.38s | 2.281s | 2315.088
| createChannel | Avg| 725ms| 833ms | 108ms | 14.895
| | P99| 2.445s| 4.725s | 2.28s | 93.250
| createDirectChannel | Avg| 457ms| 469ms | 12ms | 2.623
| | P99| 3.745s| 2.414s | -1.331s | -35.542
| createGroupChannel | Avg| 814ms| 1.125s | 311ms | 38.205
| | P99| 4.887s| 7.783s | 2.896s | 59.254
| createPost | Avg| 1.323s| 1.487s | 164ms | 12.400
| | P99| 8.046s| 8.963s | 917ms | 11.397
| createUser | Avg| 224ms| 222ms | -2ms | -0.894
| | P99| 1.536s| 1.201s | -335ms | -21.807
| deletePost | Avg| 605ms| 182ms | -423ms | -69.866
| | P99| 4.5s| 965ms | -3.535s | -78.556
| followThreadByUser | Avg| 77ms| 122ms | 45ms | 58.617
| | P99| 475ms| 950ms | 475ms | 100.000
| getAllTeams | Avg| 47ms| 52ms | 5ms | 10.717
| | P99| 484ms| 496ms | 12ms | 2.481
| getCategoriesForTeamForUser | Avg| 101ms| 116ms | 15ms | 14.780
| | P99| 981ms| 1.234s | 253ms | 25.784
| getChannel | Avg| 96ms| 105ms | 9ms | 9.339
| | P99| 981ms| 1.37s | 389ms | 39.647
| getChannelMember | Avg| 53ms| 60ms | 7ms | 13.093
| | P99| 761ms| 836ms | 75ms | 9.862
| getChannelMembers | Avg| 4ms| 26ms | 22ms | 616.175
| | P99| 5ms| 50ms | 45ms | 909.091
| getChannelMembersForTeamForUser | Avg| 48ms| 58ms | 10ms | 20.639
| | P99| 489ms| 604ms | 115ms | 23.523
| getChannelStats | Avg| 53ms| 55ms | 2ms | 3.792
| | P99| 937ms| 951ms | 14ms | 1.494
| getChannelUnread | Avg| 32ms| 42ms | 10ms | 31.623
| | P99| 417ms| 473ms | 56ms | 13.427
| getChannelsForTeamForUser | Avg| 50ms| 60ms | 10ms | 19.991
| | P99| 500ms| 687ms | 187ms | 37.424
| getChannelsForUser | Avg| 36ms| 51ms | 15ms | 41.410
| | P99| 435ms| 482ms | 47ms | 10.804
| getClientConfig | Avg| 13ms| 14ms | 1ms | 7.905
| | P99| 230ms| 237ms | 7ms | 3.044
| getFilePreview | Avg| 76ms| 80ms | 4ms | 5.276
| | P99| 481ms| 492ms | 11ms | 2.286
| getFileThumbnail | Avg| 70ms| 76ms | 6ms | 8.540
| | P99| 485ms| 499ms | 14ms | 2.885
| getPostThread | Avg| 311ms| 365ms | 54ms | 17.371
| | P99| 2.803s| 3.595s | 792ms | 28.259
| getPostsForChannel | Avg| 400ms| 502ms | 102ms | 25.484
| | P99| 5.695s| 7.485s | 1.79s | 31.432
| getPostsForChannelAroundLastUnread | Avg| 198ms| 224ms | 26ms | 13.099
| | P99| 2.337s| 2.448s | 111ms | 4.750
| getPreferences | Avg| 61ms| 66ms | 5ms | 8.223
| | P99| 578ms| 660ms | 82ms | 14.183
| getProfileImage | Avg| 96ms| 93ms | -3ms | -3.120
| | P99| 475ms| 476ms | 1ms | 0.210
| getPublicChannelsForTeam | Avg| 88ms| 79ms | -9ms | -10.223
| | P99| 843ms| 725ms | -118ms | -13.992
| getTeamMember | Avg| 5ms| 7ms | 2ms | 37.252
| | P99| 121ms| 98ms | -23ms | -19.045
| getTeamMembersForUser | Avg| 31ms| 36ms | 5ms | 16.326
| | P99| 412ms| 439ms | 27ms | 6.554
| getTeamStats | Avg| 369ms| 433ms | 64ms | 17.322
| | P99| 982ms| 986ms | 4ms | 0.407
| getTeamsForUser | Avg| 47ms| 52ms | 5ms | 10.746
| | P99| 474ms| 498ms | 24ms | 5.063
| getTeamsUnreadForUser | Avg| 68ms| 77ms | 9ms | 13.164
| | P99| 870ms| 922ms | 52ms | 5.977
| getThreadsForUser | Avg| 56ms| 67ms | 11ms | 19.574
| | P99| 679ms| 801ms | 122ms | 17.970
| getUser | Avg| 63ms| 69ms | 6ms | 9.561
| | P99| 734ms| 808ms | 74ms | 10.085
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 33ms| 36ms | 3ms | 9.049
| | P99| 470ms| 491ms | 21ms | 4.464
| getUsersByIds | Avg| 4ms| 5ms | 1ms | 22.784
| | P99| 100ms| 111ms | 11ms | 11.019
| getUsersByNames | Avg| 40ms| 47ms | 7ms | 17.312
| | P99| 472ms| 490ms | 18ms | 3.813
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 198ms| 207ms | 9ms | 4.547
| | P99| 1.952s| 2.056s | 104ms | 5.327
| logout | Avg| 219ms| 194ms | -25ms | -11.402
| | P99| 2.215s| 960ms | -1.255s | -56.660
| patchPost | Avg| 1.167s| 1.787s | 620ms | 53.149
| | P99| 6.55s| 10s | 3.45s | 52.671
| removeUserCustomStatus | Avg| 188ms| 182ms | -6ms | -3.197
| | P99| 890ms| 818ms | -72ms | -8.090
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 162ms| 194ms | 32ms | 19.733
| | P99| 1.936s| 2.187s | 251ms | 12.964
| searchAllChannels | Avg| 2.258s| 2.388s | 130ms | 5.757
| | P99| 9.453s| 9.533s | 80ms | 0.846
| searchGroupChannels | Avg| 60ms| 69ms | 9ms | 14.905
| | P99| 771ms| 767ms | -4ms | -0.519
| searchPostsInTeam | Avg| 237ms| 338ms | 101ms | 42.591
| | P99| 2.909s| 4.264s | 1.355s | 46.576
| searchUsers | Avg| 204ms| 225ms | 21ms | 10.304
| | P99| 963ms| 977ms | 14ms | 1.454
| setPostReminder | Avg| 312ms| 250ms | -62ms | -19.875
| | P99| 2.215s| 980ms | -1.235s | -55.757
| unfollowThreadByUser | Avg| 124ms| 196ms | 72ms | 58.069
| | P99| 914ms| 2.213s | 1.299s | 142.189
| updateCategoriesForTeamForUser | Avg| 372ms| 321ms | -51ms | -13.707
| | P99| 2.401s| 2.215s | -186ms | -7.745
| updatePreferences | Avg| 13ms| 14ms | 1ms | 7.680
| | P99| 201ms| 201ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 5ms | -5ms | -51.282
| updateReadStateThreadByUser | Avg| 407ms| 498ms | 91ms | 22.385
| | P99| 4.042s| 4.42s | 378ms | 9.351
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 431ms| 426ms | -5ms | -1.160
| | P99| 1s| 999ms | -1ms | -0.100
| viewChannel | Avg| 104ms| 122ms | 18ms | 17.260
| | P99| 1.089s| 1.427s | 338ms | 31.027
