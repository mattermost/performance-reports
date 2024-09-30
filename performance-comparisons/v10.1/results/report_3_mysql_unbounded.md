### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ProductNoticesStore.ClearOldNotices | avg | 1ms | 11ms | 10ms | 671.04
| SessionStore.GetSessionsExpired | avg | 51ms | 167ms | 116ms | 228.60
| ChannelStore.CreateSidebarCategory | avg | 25ms | 79ms | 54ms | 219.71
| PluginStore.Get | avg | 62ms | 139ms | 77ms | 123.84
| PostStore.GetPostReminderMetadata | avg | 76ms | 160ms | 84ms | 110.91
| EmojiStore.GetMultipleByName | avg | 49ms | 96ms | 47ms | 95.43
| PostPersistentNotificationStore.Get | avg | 6ms | 11ms | 5ms | 83.51
| PostStore.AnalyticsPostCount | avg | 1.46s | 2.661s | 1.201s | 82.25
| PostStore.SetPostReminder | avg | 9ms | 15ms | 6ms | 66.88
| UserStore.AnalyticsGetInactiveUsersCount | avg | 112ms | 186ms | 74ms | 66.08
| StatusStore.Get | avg | 67ms | 100ms | 33ms | 49.04
| UserStore.Count | avg | 345ms | 503ms | 158ms | 45.84
| SessionStore.Remove | avg | 5ms | 7ms | 2ms | 41.85
| JobStore.GetAllByTypePage | avg | 263ms | 362ms | 99ms | 37.63
| ChannelStore.GetSidebarCategory | avg | 155ms | 211ms | 56ms | 36.17
| JobStore.GetCountByStatusAndType | avg | 114ms | 151ms | 37ms | 32.57
| ChannelStore.UpdateSidebarCategories | avg | 509ms | 674ms | 165ms | 32.44
| StatusStore.UpdateExpiredDNDStatuses | avg | 9ms | 11ms | 2ms | 22.81
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 21ms | 25ms | 4ms | 18.82
| ThreadStore.GetTeamsUnreadForUser | avg | 148ms | 175ms | 27ms | 18.19
| UserStore.AnalyticsActiveCount | avg | 652ms | 753ms | 101ms | 15.48
| StatusStore.GetByIds | avg | 182ms | 210ms | 28ms | 15.35
| FileInfoStore.GetByIds | avg | 186ms | 214ms | 28ms | 15.02
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 106ms | 119ms | 13ms | 12.32
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 264ms | 295ms | 31ms | 11.76
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 114ms | 127ms | 13ms | 11.37
| ChannelStore.GetByName | avg | 102ms | 113ms | 11ms | 10.74
| SessionStore.Get | avg | 112ms | 124ms | 12ms | 10.69
| SessionStore.Save | avg | 107ms | 118ms | 11ms | 10.32
| ChannelStore.GetAllChannelMembersForUser | avg | 97ms | 107ms | 10ms | 10.29
| PostStore.GetPosts | avg | 98ms | 108ms | 10ms | 10.25
| ChannelStore.GetMemberLastViewedAt | avg | 98ms | 108ms | 10ms | 10.17
| ChannelStore.CreateDirectChannel | avg | 499ms | 548ms | 49ms | 9.81
| ThreadStore.GetTotalThreads | avg | 112ms | 123ms | 11ms | 9.80
| ThreadStore.GetTotalUnreadThreads | avg | 113ms | 124ms | 11ms | 9.70
| ThreadStore.GetTotalUnreadMentions | avg | 116ms | 127ms | 11ms | 9.52
| TeamStore.GetTeamsForUser | avg | 85ms | 93ms | 8ms | 9.40
| ReactionStore.GetForPost | avg | 161ms | 176ms | 15ms | 9.32
| UserStore.GetForLogin | avg | 98ms | 107ms | 9ms | 9.20
| ChannelStore.SaveMember | avg | 448ms | 486ms | 38ms | 8.49
| UserStore.GetProfileByIds | avg | 86ms | 93ms | 7ms | 8.11
| ChannelStore.GetPublicChannelsForTeam | avg | 191ms | 206ms | 15ms | 7.84
| ChannelStore.GetGuestCount | avg | 142ms | 153ms | 11ms | 7.76
| UserStore.IsEmpty | avg | 53ms | 57ms | 4ms | 7.60
| JobStore.GetAllByStatus | avg | 157ms | 168ms | 11ms | 7.00
| ChannelStore.CreateInitialSidebarCategories | avg | 121ms | 129ms | 8ms | 6.59
| SessionStore.GetLRUSessions | avg | 106ms | 113ms | 7ms | 6.58
| GroupStore.GetByName | avg | 78ms | 83ms | 5ms | 6.43
| TeamStore.GetAllPage | avg | 115ms | 122ms | 7ms | 6.09
| ChannelStore.GetMembersForUser | avg | 149ms | 158ms | 9ms | 6.02
| TeamStore.SaveMember | avg | 208ms | 220ms | 12ms | 5.77
| ChannelStore.AutocompleteInTeamForSearch | avg | 601ms | 632ms | 31ms | 5.16
| ChannelStore.GetChannelsByUser | avg | 127ms | 133ms | 6ms | 4.73
| UserTermsOfServiceStore.GetByUser | avg | 134ms | 140ms | 6ms | 4.48
| ChannelStore.SearchGroupChannels | avg | 181ms | 189ms | 8ms | 4.43
| ChannelStore.GetMemberCount | avg | 485ms | 503ms | 18ms | 3.71
| ThreadStore.GetMembershipForUser | avg | 163ms | 169ms | 6ms | 3.68
| PostAcknowledgementStore.GetForPosts | avg | 267ms | 276ms | 9ms | 3.36
| UserStore.GetAllProfiles | avg | 90ms | 93ms | 3ms | 3.34
| PostStore.Get | avg | 285ms | 294ms | 9ms | 3.16
| GroupStore.GetGroups | avg | 162ms | 167ms | 5ms | 3.09
| PostPersistentNotificationStore.GetSingle | avg | 170ms | 175ms | 5ms | 2.94
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 174ms | 179ms | 5ms | 2.88
| ChannelStore.Autocomplete | avg | 3.944s | 4.057s | 113ms | 2.87
| TeamStore.GetChannelUnreadsForAllTeams | avg | 115ms | 118ms | 3ms | 2.62
| ChannelStore.Get | avg | 196ms | 201ms | 5ms | 2.56
| PostPriorityStore.GetForPosts | avg | 274ms | 281ms | 7ms | 2.55
| ChannelStore.GetChannels | avg | 159ms | 163ms | 4ms | 2.51
| UserStore.GetUnreadCount | avg | 147ms | 150ms | 3ms | 2.05
| PostAcknowledgementStore.GetForPost | avg | 153ms | 156ms | 3ms | 1.97
| BotStore.Get | avg | 160ms | 163ms | 3ms | 1.88
| PreferenceStore.GetAll | avg | 160ms | 163ms | 3ms | 1.87
| WebhookStore.GetOutgoingByTeam | avg | 172ms | 175ms | 3ms | 1.74
| PostStore.SearchPostsForUser | avg | 252ms | 256ms | 4ms | 1.59
| UserStore.GetAllProfilesInChannel | avg | 1.14s | 1.157s | 17ms | 1.49
| UserStore.AutocompleteUsersInChannel | avg | 734ms | 744ms | 10ms | 1.36
| PostStore.GetEtag | avg | 153ms | 155ms | 2ms | 1.31
| PreferenceStore.Get | avg | 158ms | 160ms | 2ms | 1.26
| EmojiStore.GetByName | avg | 169ms | 171ms | 2ms | 1.18
| ThreadStore.GetThreadsForUser | avg | 184ms | 186ms | 2ms | 1.09
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.GetPostReminderMetadata | p99 | 246ms | 2.125s | 1.879s | 765.37
| ProductNoticesStore.ClearOldNotices | p99 | 5ms | 25ms | 20ms | 403.89
| ChannelStore.CreateSidebarCategory | p99 | 49ms | 246ms | 197ms | 399.53
| UserStore.Count | p99 | 979ms | 4.638s | 3.659s | 373.75
| UserStore.GetProfilesInChannel | p99 | 490ms | 2.29s | 1.8s | 367.35
| JobStore.GetCountByStatusAndType | p99 | 640ms | 2.95s | 2.31s | 360.94
| StatusStore.UpdateExpiredDNDStatuses | p99 | 47ms | 207ms | 160ms | 338.62
| PluginStore.Get | p99 | 241ms | 960ms | 719ms | 298.34
| SessionStore.GetSessionsExpired | p99 | 238ms | 940ms | 702ms | 294.94
| ChannelStore.AnalyticsTypeCount | p99 | 249ms | 960ms | 711ms | 286.12
| SessionStore.Remove | p99 | 24ms | 91ms | 67ms | 282.40
| PostStore.SetPostReminder | p99 | 25ms | 93ms | 68ms | 275.30
| ChannelStore.UpdateSidebarCategories | p99 | 2.36s | 8.001s | 5.641s | 239.02
| EmojiStore.GetMultipleByName | p99 | 99ms | 246ms | 147ms | 147.94
| UserStore.AnalyticsActiveCount | p99 | 995ms | 2.44s | 1.445s | 145.23
| ChannelStore.GetMembersForUserWithPagination | p99 | 870ms | 2.125s | 1.255s | 144.26
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 247ms | 490ms | 243ms | 98.28
| TeamStore.AnalyticsTeamCount | p99 | 249ms | 490ms | 241ms | 96.93
| JobStore.UpdateStatus | p99 | 43ms | 80ms | 37ms | 86.80
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 983ms | 1.818s | 835ms | 84.93
| StatusStore.Get | p99 | 496ms | 913ms | 417ms | 84.16
| ChannelStore.GetSidebarCategory | p99 | 790ms | 1.33s | 540ms | 68.36
| ChannelStore.CreateDirectChannel | p99 | 2.448s | 3.884s | 1.436s | 58.66
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 998ms | 1.487s | 489ms | 48.98
| ChannelStore.GetPublicChannelsForTeam | p99 | 1.42s | 1.915s | 495ms | 34.86
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.485s | 3.33s | 845ms | 34.00
| FileInfoStore.SetContent | p99 | 100ms | 132ms | 32ms | 32.07
| FileInfoStore.GetByIds | p99 | 1.677s | 2.154s | 477ms | 28.44
| ChannelStore.GetGuestCount | p99 | 971ms | 1.231s | 260ms | 26.78
| PreferenceStore.GetAll | p99 | 1.038s | 1.293s | 255ms | 24.58
| ChannelStore.GetMembersForUser | p99 | 1.251s | 1.557s | 306ms | 24.46
| ChannelStore.GetPinnedPostCount | p99 | 1.47s | 1.815s | 345ms | 23.47
| ChannelStore.SaveMember | p99 | 2.749s | 3.336s | 587ms | 21.35
| StatusStore.GetByIds | p99 | 1.679s | 2.017s | 338ms | 20.13
| ThreadStore.GetMembershipForUser | p99 | 1.481s | 1.776s | 295ms | 19.92
| UserStore.GetAllProfilesInChannel | p99 | 2.496s | 2.982s | 486ms | 19.47
| ThreadStore.GetTeamsUnreadForUser | p99 | 1.78s | 2.074s | 294ms | 16.51
| PostPersistentNotificationStore.DeleteExpired | p99 | 41ms | 47ms | 6ms | 14.63
| JobStore.GetAllByStatus | p99 | 1.672s | 1.906s | 234ms | 14.00
| PostStore.GetPosts | p99 | 804ms | 909ms | 105ms | 13.06
| PostStore.GetPostsBefore | p99 | 1.363s | 1.519s | 156ms | 11.44
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 862ms | 957ms | 95ms | 11.02
| PostStore.SearchPostsForUser | p99 | 2.022s | 2.232s | 210ms | 10.38
| SessionStore.Save | p99 | 849ms | 937ms | 88ms | 10.37
| ChannelStore.GetFileCount | p99 | 821ms | 900ms | 79ms | 9.62
| WebhookStore.GetOutgoingByTeam | p99 | 1.63s | 1.776s | 146ms | 8.95
| UserTermsOfServiceStore.GetByUser | p99 | 953ms | 1.029s | 76ms | 7.97
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 1.343s | 1.45s | 107ms | 7.97
| GroupStore.GetGroups | p99 | 1.611s | 1.735s | 124ms | 7.70
| UserStore.GetForLogin | p99 | 833ms | 897ms | 64ms | 7.68
| EmojiStore.GetByName | p99 | 1.661s | 1.785s | 124ms | 7.46
| GroupStore.GetByName | p99 | 601ms | 644ms | 43ms | 7.15
| PreferenceStore.Get | p99 | 1.475s | 1.579s | 104ms | 7.05
| StatusStore.UpdateLastActivityAt | p99 | 85ms | 91ms | 6ms | 7.03
| PostStore.GetEtag | p99 | 1.225s | 1.311s | 86ms | 7.02
| UserStore.GetUnreadCount | p99 | 1.325s | 1.413s | 88ms | 6.64
| ChannelStore.SearchGroupChannels | p99 | 1.762s | 1.876s | 114ms | 6.47
| TeamStore.GetTeamsForUser | p99 | 759ms | 808ms | 49ms | 6.45
| ChannelStore.GetByName | p99 | 902ms | 960ms | 58ms | 6.43
| ChannelStore.GetChannels | p99 | 1.478s | 1.573s | 95ms | 6.43
| ChannelStore.GetAllChannelMembersForUser | p99 | 855ms | 905ms | 50ms | 5.84
| SessionStore.Get | p99 | 908ms | 961ms | 53ms | 5.84
| ChannelStore.GetChannelUnread | p99 | 1.161s | 1.224s | 63ms | 5.43
| ReactionStore.GetForPost | p99 | 1.666s | 1.756s | 90ms | 5.40
| UserStore.UpdateFailedPasswordAttempts | p99 | 75ms | 79ms | 4ms | 5.34
| ChannelStore.Get | p99 | 1.741s | 1.832s | 91ms | 5.23
| ThreadStore.GetTotalUnreadMentions | p99 | 949ms | 991ms | 42ms | 4.42
| UserStore.GetAllProfiles | p99 | 881ms | 917ms | 36ms | 4.09
| ThreadStore.GetTotalThreads | p99 | 941ms | 977ms | 36ms | 3.83
| ChannelStore.GetMemberLastViewedAt | p99 | 878ms | 911ms | 33ms | 3.76
| SessionStore.GetLRUSessions | p99 | 880ms | 913ms | 33ms | 3.75
| TeamStore.GetAllPage | p99 | 916ms | 950ms | 34ms | 3.71
| FileInfoStore.Save | p99 | 82ms | 85ms | 3ms | 3.68
| ThreadStore.GetThreadUnreadReplyCount | p99 | 1.959s | 2.031s | 72ms | 3.68
| PostStore.Get | p99 | 2.323s | 2.406s | 83ms | 3.57
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 957ms | 990ms | 33ms | 3.45
| ChannelStore.CreateInitialSidebarCategories | p99 | 906ms | 937ms | 31ms | 3.42
| PostStore.GetPostsSince | p99 | 1.789s | 1.85s | 61ms | 3.41
| ThreadStore.GetThreadsForUser | p99 | 1.774s | 1.834s | 60ms | 3.38
| ChannelStore.UpdateLastViewedAt | p99 | 152ms | 157ms | 5ms | 3.28
| ChannelStore.IncrementMentionCount | p99 | 62ms | 64ms | 2ms | 3.23
| UserStore.GetProfileByIds | p99 | 936ms | 963ms | 27ms | 2.89
| TeamStore.SaveMember | p99 | 954ms | 980ms | 26ms | 2.72
| PostPersistentNotificationStore.GetSingle | p99 | 1.651s | 1.696s | 45ms | 2.72
| FileInfoStore.GetForPost | p99 | 1.992s | 2.045s | 53ms | 2.66
| PostStore.GetPostIdBeforeTime | p99 | 79ms | 81ms | 2ms | 2.52
| ThreadStore.GetTotalUnreadThreads | p99 | 955ms | 977ms | 22ms | 2.30
| UserStore.IsEmpty | p99 | 478ms | 489ms | 11ms | 2.30
| PostStore.Save | p99 | 217ms | 222ms | 5ms | 2.30
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 2.247s | 2.297s | 50ms | 2.23
| ThreadStore.GetThreadForUser | p99 | 2.243s | 2.281s | 38ms | 1.69
| ChannelStore.GetMemberCount | p99 | 2.187s | 2.224s | 37ms | 1.69
| ThreadStore.MaintainMembership | p99 | 182ms | 185ms | 3ms | 1.65
| PostAcknowledgementStore.GetForPosts | p99 | 2.433s | 2.473s | 40ms | 1.64
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 928ms | 943ms | 15ms | 1.62
| ChannelStore.GetMemberForPost | p99 | 1.915s | 1.944s | 29ms | 1.51
| UserStore.Search | p99 | 2.174s | 2.205s | 31ms | 1.43
| PostPriorityStore.GetForPosts | p99 | 2.451s | 2.483s | 32ms | 1.31
| UserStore.GetProfilesByUsernames | p99 | 969ms | 980ms | 11ms | 1.13
| FileInfoStore.Get | p99 | 944ms | 954ms | 10ms | 1.06
| PreferenceStore.Save | p99 | 197ms | 199ms | 2ms | 1.01
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | avg | 68ms | 0s | -68ms | -100.33
| ChannelStore.Update | avg | 55ms | 0s | -55ms | -99.99
| RetentionPolicyStore.GetAll | avg | 90ms | 0s | -90ms | -99.77
| SchemeStore.GetAllPage | avg | 17ms | 0s | -17ms | -99.74
| CommandWebhookStore.Cleanup | avg | 15ms | 1ms | -14ms | -94.98
| TokenStore.Cleanup | avg | 14ms | 1ms | -13ms | -92.00
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 238ms | 63ms | -175ms | -73.47
| ChannelStore.GetMemberCountsByGroup | avg | 13ms | 4ms | -9ms | -70.65
| StatusStore.SaveOrUpdate | avg | 24ms | 8ms | -16ms | -65.90
| RoleStore.ChannelHigherScopedPermissions | avg | 230ms | 84ms | -146ms | -63.49
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 131ms | 62ms | -69ms | -52.49
| ProductNoticesStore.GetViews | avg | 103ms | 52ms | -51ms | -49.57
| PostStore.Delete | avg | 282ms | 160ms | -122ms | -43.25
| ChannelStore.GetMembersForUserWithPagination | avg | 255ms | 146ms | -109ms | -42.82
| UserStore.GetProfilesNotInChannel | avg | 208ms | 122ms | -86ms | -41.33
| TeamStore.AnalyticsTeamCount | avg | 177ms | 104ms | -73ms | -41.30
| LicenseStore.GetAll | avg | 296ms | 181ms | -115ms | -38.87
| UserStore.Update | avg | 16ms | 10ms | -6ms | -37.57
| ComplianceStore.MessageExport | avg | 204ms | 128ms | -76ms | -37.21
| TeamStore.GetActiveMemberCount | avg | 615ms | 395ms | -220ms | -35.76
| JobStore.Get | avg | 236ms | 160ms | -76ms | -32.21
| PostStore.GetPostReminders | avg | 13ms | 9ms | -4ms | -31.71
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 1.071s | 750ms | -321ms | -29.97
| TeamStore.GetTotalMemberCount | avg | 445ms | 334ms | -111ms | -24.94
| ThreadStore.Get | avg | 243ms | 185ms | -58ms | -23.85
| RoleStore.GetByNames | avg | 184ms | 146ms | -38ms | -20.64
| UserStore.GetByUsername | avg | 192ms | 155ms | -37ms | -19.24
| ChannelStore.Save | avg | 229ms | 187ms | -42ms | -18.37
| PluginStore.List | avg | 198ms | 162ms | -36ms | -18.21
| UserAccessTokenStore.GetByToken | avg | 58ms | 49ms | -9ms | -15.64
| PostStore.GetPostsAfter | avg | 165ms | 144ms | -21ms | -12.70
| PostStore.Update | avg | 27ms | 24ms | -3ms | -11.20
| UserStore.GetMany | avg | 198ms | 178ms | -20ms | -10.12
| ChannelStore.GetChannelUnread | avg | 145ms | 133ms | -12ms | -8.28
| ChannelStore.AnalyticsTypeCount | avg | 172ms | 161ms | -11ms | -6.40
| FileInfoStore.Get | avg | 123ms | 116ms | -7ms | -5.71
| PostPriorityStore.GetForPost | avg | 134ms | 127ms | -7ms | -5.21
| TeamStore.GetTeamsByUserId | avg | 123ms | 117ms | -6ms | -4.89
| PostStore.GetPostsByThread | avg | 181ms | 173ms | -8ms | -4.42
| ChannelStore.GetTeamChannels | avg | 290ms | 283ms | -7ms | -2.42
| UserStore.GetProfilesByUsernames | avg | 133ms | 130ms | -3ms | -2.25
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 190ms | 186ms | -4ms | -2.10
| DraftStore.Get | avg | 206ms | 202ms | -4ms | -1.94
| ChannelStore.GetMembers | avg | 106ms | 104ms | -2ms | -1.88
| PostStore.GetSingle | avg | 170ms | 167ms | -3ms | -1.76
| LinkMetadataStore.Get | avg | 173ms | 170ms | -3ms | -1.74
| ThreadStore.GetThreadFollowers | avg | 176ms | 173ms | -3ms | -1.70
| ChannelStore.GetMemberForPost | avg | 198ms | 195ms | -3ms | -1.52
| UserStore.Search | avg | 407ms | 402ms | -5ms | -1.23
| ThreadStore.GetThreadUnreadReplyCount | avg | 193ms | 191ms | -2ms | -1.04
| FileInfoStore.GetForPost | avg | 196ms | 194ms | -2ms | -1.02
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | p99 | 25ms | 0s | -25ms | -100.60
| RetentionPolicyStore.GetAll | p99 | 100ms | 0s | -100ms | -100.50
| ChannelStore.Update | p99 | 100ms | 0s | -100ms | -100.50
| RetentionPolicyStore.GetCount | p99 | 100ms | 0s | -100ms | -100.50
| TokenStore.Cleanup | p99 | 25ms | 5ms | -20ms | -80.97
| CommandWebhookStore.Cleanup | p99 | 25ms | 5ms | -20ms | -80.97
| StatusStore.SaveOrUpdate | p99 | 439ms | 89ms | -350ms | -79.68
| RoleStore.ChannelHigherScopedPermissions | p99 | 2.284s | 489ms | -1.795s | -78.60
| ChannelStore.GetMemberCountsByGroup | p99 | 199ms | 45ms | -154ms | -77.39
| JobStore.GetAllByTypePage | p99 | 7.849s | 2.376s | -5.473s | -69.73
| UserStore.Update | p99 | 252ms | 90ms | -162ms | -64.16
| ThreadStore.Get | p99 | 2.495s | 985ms | -1.51s | -60.52
| PostStore.Delete | p99 | 2.32s | 930ms | -1.39s | -59.91
| PostStore.GetPostReminders | p99 | 94ms | 46ms | -48ms | -50.79
| LicenseStore.GetAll | p99 | 975ms | 488ms | -487ms | -49.95
| TeamStore.GetTotalMemberCount | p99 | 980ms | 497ms | -483ms | -49.28
| UserStore.GetByUsername | p99 | 1.938s | 987ms | -951ms | -49.08
| PluginStore.List | p99 | 1.81s | 942ms | -868ms | -47.96
| RoleStore.GetByNames | p99 | 1.075s | 565ms | -510ms | -47.44
| PostAcknowledgementStore.GetForPost | p99 | 1.889s | 994ms | -895ms | -47.39
| UserAccessTokenStore.GetByToken | p99 | 456ms | 244ms | -212ms | -46.47
| JobStore.Save | p99 | 160ms | 87ms | -73ms | -45.63
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 1.815s | 992ms | -823ms | -45.35
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 4.322s | 2.474s | -1.848s | -42.76
| JobStore.GetNewestJobByStatusesAndType | p99 | 1.495s | 919ms | -576ms | -38.53
| ComplianceStore.MessageExport | p99 | 2.164s | 1.497s | -667ms | -30.82
| PostPriorityStore.GetForPost | p99 | 1.185s | 945ms | -240ms | -20.26
| JobStore.Get | p99 | 2.102s | 1.694s | -408ms | -19.41
| ChannelStore.Save | p99 | 1.802s | 1.457s | -345ms | -19.14
| UserStore.Save | p99 | 332ms | 276ms | -56ms | -16.85
| UserStore.UpdateUpdateAt | p99 | 61ms | 51ms | -10ms | -16.41
| JobStore.UpdateStatusOptimistically | p99 | 70ms | 59ms | -11ms | -15.71
| PostStore.GetPostsAfter | p99 | 1.92s | 1.676s | -244ms | -12.71
| PostStore.Update | p99 | 192ms | 170ms | -22ms | -11.46
| BotStore.Get | p99 | 945ms | 855ms | -90ms | -9.52
| PostPersistentNotificationStore.Get | p99 | 196ms | 178ms | -18ms | -9.18
| FileInfoStore.AttachToPost | p99 | 89ms | 81ms | -8ms | -9.02
| DraftStore.Delete | p99 | 92ms | 84ms | -8ms | -8.73
| DraftStore.GetDraftsForUser | p99 | 1.843s | 1.689s | -154ms | -8.36
| TeamStore.GetMember | p99 | 225ms | 208ms | -17ms | -7.57
| SystemStore.GetByName | p99 | 54ms | 50ms | -4ms | -7.40
| ChannelStore.GetMember | p99 | 165ms | 154ms | -11ms | -6.68
| LinkMetadataStore.Save | p99 | 77ms | 72ms | -5ms | -6.49
| JobStore.UpdateOptimistically | p99 | 93ms | 87ms | -6ms | -6.42
| ThreadStore.MarkAllAsReadByChannels | p99 | 94ms | 88ms | -6ms | -6.36
| PluginStore.Delete | p99 | 44ms | 42ms | -2ms | -4.50
| UserStore.GetProfilesNotInChannel | p99 | 495ms | 475ms | -20ms | -4.04
| ProductNoticesStore.View | p99 | 421ms | 404ms | -17ms | -4.04
| PluginStore.SetWithOptions | p99 | 95ms | 92ms | -3ms | -3.16
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 65ms | 63ms | -2ms | -3.07
| AuditStore.Save | p99 | 76ms | 74ms | -2ms | -2.63
| TeamStore.GetTeamsByUserId | p99 | 947ms | 925ms | -22ms | -2.32
| LinkMetadataStore.Get | p99 | 1.81s | 1.768s | -42ms | -2.32
| TeamStore.GetActiveMemberCount | p99 | 993ms | 975ms | -18ms | -1.81
| PostStore.GetSingle | p99 | 1.785s | 1.756s | -29ms | -1.62
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | avg | 254ms | 894ms | 640ms | 252.14
| createCategoryForTeamForUser | avg | 141ms | 416ms | 275ms | 195.67
| getFilteredUsersStats | avg | 317ms | 891ms | 574ms | 181.05
| getTeamMember | avg | 13ms | 20ms | 7ms | 55.71
| getJobsByType | avg | 263ms | 363ms | 100ms | 37.98
| patchPost | avg | 1.203s | 1.658s | 455ms | 37.83
| followThreadByUser | avg | 367ms | 489ms | 122ms | 33.23
| updateCategoriesForTeamForUser | avg | 979ms | 1.268s | 289ms | 29.53
| logout | avg | 236ms | 271ms | 35ms | 14.82
| getPostsForChannelAroundLastUnread | avg | 517ms | 592ms | 75ms | 14.49
| getCategoriesForTeamForUser | avg | 264ms | 295ms | 31ms | 11.73
| getAnalytics | avg | 1.157s | 1.282s | 125ms | 10.80
| createPost | avg | 3.668s | 4.054s | 386ms | 10.52
| getTeamMembersForUser | avg | 93ms | 102ms | 9ms | 9.72
| getPublicChannelsForTeam | avg | 193ms | 207ms | 14ms | 7.25
| addChannelMember | avg | 2.303s | 2.456s | 153ms | 6.64
| getAllTeams | avg | 122ms | 130ms | 8ms | 6.57
| getTeamsUnreadForUser | avg | 186ms | 198ms | 12ms | 6.46
| autocompleteChannelsForTeamForSearch | avg | 601ms | 632ms | 31ms | 5.16
| getChannelMembersForTeamForUser | avg | 151ms | 158ms | 7ms | 4.64
| searchGroupChannels | avg | 181ms | 189ms | 8ms | 4.42
| getThreadsForUser | avg | 184ms | 192ms | 8ms | 4.35
| login | avg | 435ms | 449ms | 14ms | 3.22
| getUser | avg | 161ms | 166ms | 5ms | 3.11
| getChannelsForUser | avg | 129ms | 133ms | 4ms | 3.11
| searchAllChannels | avg | 3.947s | 4.067s | 120ms | 3.04
| addTeamMember | avg | 3.584s | 3.683s | 99ms | 2.76
| saveReaction | avg | 527ms | 539ms | 12ms | 2.28
| getPreferences | avg | 163ms | 166ms | 3ms | 1.84
| getDrafts | avg | 188ms | 191ms | 3ms | 1.59
| autocompleteUsers | avg | 663ms | 673ms | 10ms | 1.51
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | p99 | 495ms | 9.35s | 8.855s | 1788.08
| getFilteredUsersStats | p99 | 985ms | 4.9s | 3.915s | 397.46
| createCategoryForTeamForUser | p99 | 493ms | 2.425s | 1.932s | 392.27
| followThreadByUser | p99 | 980ms | 4.65s | 3.67s | 374.49
| updateCategoriesForTeamForUser | p99 | 2.465s | 8.001s | 5.536s | 224.58
| getTeamMember | p99 | 238ms | 386ms | 148ms | 62.09
| getUser | p99 | 1.087s | 1.566s | 479ms | 44.08
| getPublicChannelsForTeam | p99 | 1.42s | 1.915s | 495ms | 34.86
| autocompleteChannelsForTeamForSearch | p99 | 2.485s | 3.33s | 845ms | 34.00
| patchPost | p99 | 8.067s | 10s | 1.933s | 23.96
| getChannelMembersForTeamForUser | p99 | 1.263s | 1.552s | 289ms | 22.89
| getPreferences | p99 | 1.137s | 1.382s | 245ms | 21.55
| login | p99 | 2.61s | 3.084s | 474ms | 18.16
| getUserStatusesByIds | p99 | 12ms | 14ms | 2ms | 16.40
| getPostThread | p99 | 5.956s | 6.687s | 731ms | 12.27
| getPostsForChannelAroundLastUnread | p99 | 4.171s | 4.592s | 421ms | 10.09
| getUsers | p99 | 696ms | 751ms | 55ms | 7.90
| getChannelUnread | p99 | 1.272s | 1.371s | 99ms | 7.78
| getUsersByIds | p99 | 317ms | 339ms | 22ms | 6.94
| searchGroupChannels | p99 | 1.762s | 1.876s | 114ms | 6.47
| saveReaction | p99 | 3.616s | 3.849s | 233ms | 6.44
| getTeamsUnreadForUser | p99 | 2.036s | 2.147s | 111ms | 5.45
| getFilePreview | p99 | 1.375s | 1.446s | 71ms | 5.16
| getTeamMembersForUser | p99 | 845ms | 881ms | 36ms | 4.26
| createGroupChannel | p99 | 9.57s | 9.913s | 343ms | 3.58
| getFileThumbnail | p99 | 1.499s | 1.552s | 53ms | 3.54
| getChannelsForTeamForUser | p99 | 1.496s | 1.544s | 48ms | 3.21
| getThreadsForUser | p99 | 1.959s | 2.021s | 62ms | 3.17
| getAllTeams | p99 | 947ms | 975ms | 28ms | 2.96
| getClientConfig | p99 | 431ms | 442ms | 11ms | 2.55
| getCategoriesForTeamForUser | p99 | 2.251s | 2.299s | 48ms | 2.13
| logout | p99 | 958ms | 970ms | 12ms | 1.25
| getUsersByNames | p99 | 976ms | 986ms | 10ms | 1.02
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 15ms | 4ms | -11ms | -72.04
| getChannelMembersForUser | avg | 221ms | 69ms | -152ms | -68.85
| getTeamStats | avg | 852ms | 420ms | -432ms | -50.69
| getUsersByGroupChannelIds | avg | 240ms | 123ms | -117ms | -48.69
| createChannel | avg | 3.289s | 1.808s | -1.481s | -45.03
| deletePost | avg | 966ms | 557ms | -409ms | -42.35
| getChannel | avg | 499ms | 320ms | -179ms | -35.89
| unfollowThreadByUser | avg | 492ms | 378ms | -114ms | -23.19
| removeUserCustomStatus | avg | 261ms | 207ms | -54ms | -20.71
| getChannelMember | avg | 171ms | 142ms | -29ms | -17.00
| getChannelStats | avg | 145ms | 125ms | -20ms | -13.82
| getRolesByNames | avg | 130ms | 113ms | -17ms | -13.06
| getPrevTrialLicense | avg | 261ms | 232ms | -29ms | -11.12
| createDirectChannel | avg | 1.141s | 1.022s | -119ms | -10.43
| createGroupChannel | avg | 2.84s | 2.559s | -281ms | -9.89
| searchPostsInTeam | avg | 617ms | 556ms | -61ms | -9.89
| createUser | avg | 368ms | 335ms | -33ms | -8.98
| getChannelUnread | avg | 154ms | 142ms | -12ms | -7.80
| getFileThumbnail | avg | 191ms | 182ms | -9ms | -4.72
| getFilePreview | avg | 196ms | 187ms | -9ms | -4.59
| getProfileImage | avg | 94ms | 90ms | -4ms | -4.26
| updateReadStateThreadByUser | avg | 1.379s | 1.322s | -57ms | -4.13
| getTeamsForUser | avg | 123ms | 118ms | -5ms | -4.06
| upsertDraft | avg | 76ms | 74ms | -2ms | -2.62
| getChannelsForTeamForUser | avg | 164ms | 160ms | -4ms | -2.44
| uploadFileStream | avg | 428ms | 418ms | -10ms | -2.33
| getUsersByNames | avg | 135ms | 132ms | -3ms | -2.22
| searchUsers | avg | 413ms | 405ms | -8ms | -1.94
| getChannelMembers | avg | 107ms | 105ms | -2ms | -1.87
| deleteDraft | avg | 206ms | 203ms | -3ms | -1.45
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | p99 | 216ms | 45ms | -171ms | -79.06
| deletePost | p99 | 9.4s | 2.29s | -7.11s | -75.64
| getJobsByType | p99 | 7.849s | 2.376s | -5.473s | -69.73
| getTeamStats | p99 | 2.47s | 983ms | -1.487s | -60.20
| getChannelMembersForUser | p99 | 496ms | 246ms | -250ms | -50.38
| unfollowThreadByUser | p99 | 3.862s | 2.203s | -1.659s | -42.95
| getChannel | p99 | 4.3s | 2.467s | -1.833s | -42.63
| searchPostsInTeam | p99 | 7.25s | 4.891s | -2.359s | -32.54
| getChannelMember | p99 | 1.678s | 1.562s | -116ms | -6.91
| getDrafts | p99 | 1.926s | 1.806s | -120ms | -6.23
| removeUserCustomStatus | p99 | 1.045s | 983ms | -62ms | -5.93
| uploadFileStream | p99 | 1.686s | 1.597s | -89ms | -5.28
| updateReadStateThreadByUser | p99 | 8.644s | 8.281s | -363ms | -4.20
| getChannelStats | p99 | 2.023s | 1.951s | -72ms | -3.56
| createUser | p99 | 2.239s | 2.163s | -76ms | -3.39
| createChannel | p99 | 9.75s | 9.45s | -300ms | -3.08
| updatePreferences | p99 | 237ms | 231ms | -6ms | -2.53
| getTeamsForUser | p99 | 948ms | 926ms | -22ms | -2.32
| getRolesByNames | p99 | 965ms | 945ms | -20ms | -2.07
| addChannelMember | p99 | 9.792s | 9.625s | -167ms | -1.71
| createDirectChannel | p99 | 4.827s | 4.75s | -77ms | -1.60
| upsertDraft | p99 | 979ms | 965ms | -14ms | -1.43
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 6ms | -1ms | -15.140
| |  P99| 76ms| 74ms | -2ms | -2.628
| BotStore.Get |  Avg| 160ms| 163ms | 3ms | 1.878
| |  P99| 945ms| 855ms | -90ms | -9.524
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 1.071s| 750ms | -321ms | -29.974
| |  P99| 4.322s| 2.474s | -1.848s | -42.758
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 6ms| 5ms | -1ms | -17.784
| |  P99| 65ms| 63ms | -2ms | -3.075
| ChannelStore.AnalyticsTypeCount |  Avg| 172ms| 161ms | -11ms | -6.401
| |  P99| 249ms| 960ms | 711ms | 286.117
| ChannelStore.Autocomplete |  Avg| 3.944s| 4.057s | 113ms | 2.865
| |  P99| 9.886s| 9.893s | 7ms | 0.071
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 601ms| 632ms | 31ms | 5.158
| |  P99| 2.485s| 3.33s | 845ms | 34.004
| ChannelStore.CreateDirectChannel |  Avg| 499ms| 548ms | 49ms | 9.813
| |  P99| 2.448s| 3.884s | 1.436s | 58.656
| ChannelStore.CreateInitialSidebarCategories |  Avg| 121ms| 129ms | 8ms | 6.592
| |  P99| 906ms| 937ms | 31ms | 3.423
| ChannelStore.CreateSidebarCategory |  Avg| 25ms| 79ms | 54ms | 219.710
| |  P99| 49ms| 246ms | 197ms | 399.526
| ChannelStore.Get |  Avg| 196ms| 201ms | 5ms | 2.557
| |  P99| 1.741s| 1.832s | 91ms | 5.228
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 190ms| 186ms | -4ms | -2.104
| |  P99| 1.815s| 992ms | -823ms | -45.348
| ChannelStore.GetAllChannelMembersForUser |  Avg| 97ms| 107ms | 10ms | 10.288
| |  P99| 855ms| 905ms | 50ms | 5.845
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 174ms| 179ms | 5ms | 2.877
| |  P99| 983ms| 1.818s | 835ms | 84.929
| ChannelStore.GetByName |  Avg| 102ms| 113ms | 11ms | 10.736
| |  P99| 902ms| 960ms | 58ms | 6.430
| ChannelStore.GetChannelUnread |  Avg| 145ms| 133ms | -12ms | -8.278
| |  P99| 1.161s| 1.224s | 63ms | 5.427
| ChannelStore.GetChannels |  Avg| 159ms| 163ms | 4ms | 2.511
| |  P99| 1.478s| 1.573s | 95ms | 6.428
| ChannelStore.GetChannelsByUser |  Avg| 127ms| 133ms | 6ms | 4.730
| |  P99| 941ms| 943ms | 2ms | 0.213
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 149ms| 149ms | 0s | 0.000
| |  P99| 1.343s| 1.45s | 107ms | 7.968
| ChannelStore.GetFileCount |  Avg| 119ms| 118ms | -1ms | -0.842
| |  P99| 821ms| 900ms | 79ms | 9.619
| ChannelStore.GetGuestCount |  Avg| 142ms| 153ms | 11ms | 7.756
| |  P99| 971ms| 1.231s | 260ms | 26.778
| ChannelStore.GetMember |  Avg| 9ms| 8ms | -1ms | -10.700
| |  P99| 165ms| 154ms | -11ms | -6.680
| ChannelStore.GetMemberCount |  Avg| 485ms| 503ms | 18ms | 3.714
| |  P99| 2.187s| 2.224s | 37ms | 1.692
| ChannelStore.GetMemberCountsByGroup |  Avg| 13ms| 4ms | -9ms | -70.653
| |  P99| 199ms| 45ms | -154ms | -77.387
| ChannelStore.GetMemberForPost |  Avg| 198ms| 195ms | -3ms | -1.515
| |  P99| 1.915s| 1.944s | 29ms | 1.514
| ChannelStore.GetMemberLastViewedAt |  Avg| 98ms| 108ms | 10ms | 10.167
| |  P99| 878ms| 911ms | 33ms | 3.761
| ChannelStore.GetMembers |  Avg| 106ms| 104ms | -2ms | -1.882
| |  P99| 246ms| 247ms | 1ms | 0.406
| ChannelStore.GetMembersForUser |  Avg| 149ms| 158ms | 9ms | 6.025
| |  P99| 1.251s| 1.557s | 306ms | 24.465
| ChannelStore.GetMembersForUserWithPagination |  Avg| 255ms| 146ms | -109ms | -42.820
| |  P99| 870ms| 2.125s | 1.255s | 144.257
| ChannelStore.GetPinnedPostCount |  Avg| 168ms| 169ms | 1ms | 0.594
| |  P99| 1.47s| 1.815s | 345ms | 23.470
| ChannelStore.GetPublicChannelsForTeam |  Avg| 191ms| 206ms | 15ms | 7.837
| |  P99| 1.42s| 1.915s | 495ms | 34.862
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 264ms| 295ms | 31ms | 11.762
| |  P99| 2.247s| 2.297s | 50ms | 2.225
| ChannelStore.GetSidebarCategory |  Avg| 155ms| 211ms | 56ms | 36.168
| |  P99| 790ms| 1.33s | 540ms | 68.357
| ChannelStore.GetTeamChannels |  Avg| 290ms| 283ms | -7ms | -2.418
| |  P99| 975ms| 973ms | -2ms | -0.205
| ChannelStore.IncrementMentionCount |  Avg| 5ms| 4ms | -1ms | -22.020
| |  P99| 62ms| 64ms | 2ms | 3.231
| ChannelStore.Save |  Avg| 229ms| 187ms | -42ms | -18.368
| |  P99| 1.802s| 1.457s | -345ms | -19.141
| ChannelStore.SaveMember |  Avg| 448ms| 486ms | 38ms | 8.487
| |  P99| 2.749s| 3.336s | 587ms | 21.354
| ChannelStore.SearchGroupChannels |  Avg| 181ms| 189ms | 8ms | 4.430
| |  P99| 1.762s| 1.876s | 114ms | 6.472
| ChannelStore.Update |  Avg| 55ms| 0s | -55ms | -99.985
| |  P99| 100ms| 0s | -100ms | -100.503
| ChannelStore.UpdateLastViewedAt |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 152ms| 157ms | 5ms | 3.281
| ChannelStore.UpdateSidebarCategories |  Avg| 509ms| 674ms | 165ms | 32.440
| |  P99| 2.36s| 8.001s | 5.641s | 239.024
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.041
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 6ms| 7ms | 1ms | 16.850
| |  P99| 77ms| 76ms | -1ms | -1.299
| CommandWebhookStore.Cleanup |  Avg| 15ms| 1ms | -14ms | -94.978
| |  P99| 25ms| 5ms | -20ms | -80.972
| ComplianceStore.MessageExport |  Avg| 204ms| 128ms | -76ms | -37.207
| |  P99| 2.164s| 1.497s | -667ms | -30.823
| DraftStore.Delete |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 92ms| 84ms | -8ms | -8.726
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 21ms| 25ms | 4ms | 18.819
| |  P99| 49ms| 50ms | 1ms | 2.024
| DraftStore.Get |  Avg| 206ms| 202ms | -4ms | -1.943
| |  P99| 1.993s| 2.011s | 18ms | 0.903
| DraftStore.GetDraftsForUser |  Avg| 182ms| 183ms | 1ms | 0.551
| |  P99| 1.843s| 1.689s | -154ms | -8.357
| DraftStore.Upsert |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 84ms| 84ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 169ms| 171ms | 2ms | 1.183
| |  P99| 1.661s| 1.785s | 124ms | 7.464
| EmojiStore.GetMultipleByName |  Avg| 49ms| 96ms | 47ms | 95.431
| |  P99| 99ms| 246ms | 147ms | 147.939
| FileInfoStore.AttachToPost |  Avg| 9ms| 8ms | -1ms | -11.624
| |  P99| 89ms| 81ms | -8ms | -9.025
| FileInfoStore.Get |  Avg| 123ms| 116ms | -7ms | -5.710
| |  P99| 944ms| 954ms | 10ms | 1.059
| FileInfoStore.GetByIds |  Avg| 186ms| 214ms | 28ms | 15.025
| |  P99| 1.677s| 2.154s | 477ms | 28.442
| FileInfoStore.GetForPost |  Avg| 196ms| 194ms | -2ms | -1.021
| |  P99| 1.992s| 2.045s | 53ms | 2.661
| FileInfoStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 82ms| 85ms | 3ms | 3.679
| FileInfoStore.SetContent |  Avg| 13ms| 14ms | 1ms | 7.767
| |  P99| 100ms| 132ms | 32ms | 32.069
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 106ms| 119ms | 13ms | 12.318
| |  P99| 862ms| 957ms | 95ms | 11.020
| GroupStore.GetByName |  Avg| 78ms| 83ms | 5ms | 6.425
| |  P99| 601ms| 644ms | 43ms | 7.152
| GroupStore.GetGroups |  Avg| 162ms| 167ms | 5ms | 3.093
| |  P99| 1.611s| 1.735s | 124ms | 7.698
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 131ms| 62ms | -69ms | -52.488
| |  P99| 249ms| 247ms | -2ms | -0.805
| JobStore.Get |  Avg| 236ms| 160ms | -76ms | -32.210
| |  P99| 2.102s| 1.694s | -408ms | -19.413
| JobStore.GetAllByStatus |  Avg| 157ms| 168ms | 11ms | 7.005
| |  P99| 1.672s| 1.906s | 234ms | 13.999
| JobStore.GetAllByTypePage |  Avg| 263ms| 362ms | 99ms | 37.633
| |  P99| 7.849s| 2.376s | -5.473s | -69.726
| JobStore.GetCountByStatusAndType |  Avg| 114ms| 151ms | 37ms | 32.566
| |  P99| 640ms| 2.95s | 2.31s | 360.938
| JobStore.GetNewestJobByStatusesAndType |  Avg| 127ms| 127ms | 0s | 0.000
| |  P99| 1.495s| 919ms | -576ms | -38.528
| JobStore.Save |  Avg| 9ms| 10ms | 1ms | 10.921
| |  P99| 160ms| 87ms | -73ms | -45.625
| JobStore.UpdateOptimistically |  Avg| 9ms| 8ms | -1ms | -10.732
| |  P99| 93ms| 87ms | -6ms | -6.422
| JobStore.UpdateStatus |  Avg| 5ms| 6ms | 1ms | 21.899
| |  P99| 43ms| 80ms | 37ms | 86.804
| JobStore.UpdateStatusOptimistically |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 70ms| 59ms | -11ms | -15.714
| LicenseStore.GetAll |  Avg| 296ms| 181ms | -115ms | -38.866
| |  P99| 975ms| 488ms | -487ms | -49.949
| LinkMetadataStore.Get |  Avg| 173ms| 170ms | -3ms | -1.738
| |  P99| 1.81s| 1.768s | -42ms | -2.321
| LinkMetadataStore.Save |  Avg| 8ms| 7ms | -1ms | -12.328
| |  P99| 77ms| 72ms | -5ms | -6.494
| PluginStore.Delete |  Avg| 4ms| 3ms | -1ms | -27.396
| |  P99| 44ms| 42ms | -2ms | -4.505
| PluginStore.Get |  Avg| 62ms| 139ms | 77ms | 123.845
| |  P99| 241ms| 960ms | 719ms | 298.340
| PluginStore.List |  Avg| 198ms| 162ms | -36ms | -18.214
| |  P99| 1.81s| 942ms | -868ms | -47.956
| PluginStore.SetWithOptions |  Avg| 9ms| 8ms | -1ms | -11.454
| |  P99| 95ms| 92ms | -3ms | -3.159
| PostAcknowledgementStore.GetForPost |  Avg| 153ms| 156ms | 3ms | 1.967
| |  P99| 1.889s| 994ms | -895ms | -47.387
| PostAcknowledgementStore.GetForPosts |  Avg| 267ms| 276ms | 9ms | 3.365
| |  P99| 2.433s| 2.473s | 40ms | 1.644
| PostPersistentNotificationStore.DeleteExpired |  Avg| 3ms| 4ms | 1ms | 33.123
| |  P99| 41ms| 47ms | 6ms | 14.633
| PostPersistentNotificationStore.Get |  Avg| 6ms| 11ms | 5ms | 83.505
| |  P99| 196ms| 178ms | -18ms | -9.183
| PostPersistentNotificationStore.GetSingle |  Avg| 170ms| 175ms | 5ms | 2.938
| |  P99| 1.651s| 1.696s | 45ms | 2.725
| PostPriorityStore.GetForPost |  Avg| 134ms| 127ms | -7ms | -5.209
| |  P99| 1.185s| 945ms | -240ms | -20.255
| PostPriorityStore.GetForPosts |  Avg| 274ms| 281ms | 7ms | 2.554
| |  P99| 2.451s| 2.483s | 32ms | 1.306
| PostStore.AnalyticsPostCount |  Avg| 1.46s| 2.661s | 1.201s | 82.246
| |  P99| 4.95s| 4.963s | 13ms | 0.263
| PostStore.Delete |  Avg| 282ms| 160ms | -122ms | -43.252
| |  P99| 2.32s| 930ms | -1.39s | -59.914
| PostStore.Get |  Avg| 285ms| 294ms | 9ms | 3.160
| |  P99| 2.323s| 2.406s | 83ms | 3.572
| PostStore.GetEtag |  Avg| 153ms| 155ms | 2ms | 1.309
| |  P99| 1.225s| 1.311s | 86ms | 7.019
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 65ms| 66ms | 1ms | 1.535
| PostStore.GetPostIdBeforeTime |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 81ms | 2ms | 2.521
| PostStore.GetPostReminderMetadata |  Avg| 76ms| 160ms | 84ms | 110.913
| |  P99| 246ms| 2.125s | 1.879s | 765.371
| PostStore.GetPostReminders |  Avg| 13ms| 9ms | -4ms | -31.711
| |  P99| 94ms| 46ms | -48ms | -50.794
| PostStore.GetPosts |  Avg| 98ms| 108ms | 10ms | 10.247
| |  P99| 804ms| 909ms | 105ms | 13.060
| PostStore.GetPostsAfter |  Avg| 165ms| 144ms | -21ms | -12.700
| |  P99| 1.92s| 1.676s | -244ms | -12.709
| PostStore.GetPostsBefore |  Avg| 161ms| 162ms | 1ms | 0.620
| |  P99| 1.363s| 1.519s | 156ms | 11.442
| PostStore.GetPostsByThread |  Avg| 181ms| 173ms | -8ms | -4.415
| |  P99| 1.767s| 1.76s | -7ms | -0.396
| PostStore.GetPostsSince |  Avg| 212ms| 214ms | 2ms | 0.943
| |  P99| 1.789s| 1.85s | 61ms | 3.410
| PostStore.GetSingle |  Avg| 170ms| 167ms | -3ms | -1.763
| |  P99| 1.785s| 1.756s | -29ms | -1.625
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 217ms| 222ms | 5ms | 2.300
| PostStore.SearchPostsForUser |  Avg| 252ms| 256ms | 4ms | 1.588
| |  P99| 2.022s| 2.232s | 210ms | 10.384
| PostStore.SetPostReminder |  Avg| 9ms| 15ms | 6ms | 66.881
| |  P99| 25ms| 93ms | 68ms | 275.303
| PostStore.Update |  Avg| 27ms| 24ms | -3ms | -11.198
| |  P99| 192ms| 170ms | -22ms | -11.458
| PreferenceStore.DeleteCategoryAndName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 158ms| 160ms | 2ms | 1.264
| |  P99| 1.475s| 1.579s | 104ms | 7.053
| PreferenceStore.GetAll |  Avg| 160ms| 163ms | 3ms | 1.872
| |  P99| 1.038s| 1.293s | 255ms | 24.576
| PreferenceStore.Save |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 197ms| 199ms | 2ms | 1.013
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 11ms | 10ms | 671.036
| |  P99| 5ms| 25ms | 20ms | 403.891
| ProductNoticesStore.GetViews |  Avg| 103ms| 52ms | -51ms | -49.568
| |  P99| 249ms| 247ms | -2ms | -0.805
| ProductNoticesStore.View |  Avg| 47ms| 46ms | -1ms | -2.137
| |  P99| 421ms| 404ms | -17ms | -4.039
| ReactionStore.GetForPost |  Avg| 161ms| 176ms | 15ms | 9.318
| |  P99| 1.666s| 1.756s | 90ms | 5.402
| RetentionPolicyStore.GetAll |  Avg| 90ms| 0s | -90ms | -99.766
| |  P99| 100ms| 0s | -100ms | -100.503
| RetentionPolicyStore.GetCount |  Avg| 68ms| 0s | -68ms | -100.328
| |  P99| 100ms| 0s | -100ms | -100.503
| RoleStore.ChannelHigherScopedPermissions |  Avg| 230ms| 84ms | -146ms | -63.488
| |  P99| 2.284s| 489ms | -1.795s | -78.605
| RoleStore.GetByNames |  Avg| 184ms| 146ms | -38ms | -20.639
| |  P99| 1.075s| 565ms | -510ms | -47.442
| SchemeStore.GetAllPage |  Avg| 17ms| 0s | -17ms | -99.737
| |  P99| 25ms| 0s | -25ms | -100.604
| SessionStore.Get |  Avg| 112ms| 124ms | 12ms | 10.687
| |  P99| 908ms| 961ms | 53ms | 5.840
| SessionStore.GetLRUSessions |  Avg| 106ms| 113ms | 7ms | 6.576
| |  P99| 880ms| 913ms | 33ms | 3.751
| SessionStore.GetSessionsExpired |  Avg| 51ms| 167ms | 116ms | 228.603
| |  P99| 238ms| 940ms | 702ms | 294.935
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 140ms| 140ms | 0s | 0.000
| |  P99| 998ms| 1.487s | 489ms | 48.981
| SessionStore.Remove |  Avg| 5ms| 7ms | 2ms | 41.846
| |  P99| 24ms| 91ms | 67ms | 282.405
| SessionStore.Save |  Avg| 107ms| 118ms | 11ms | 10.319
| |  P99| 849ms| 937ms | 88ms | 10.366
| SessionStore.UpdateLastActivityAt |  Avg| 7ms| 6ms | -1ms | -15.139
| |  P99| 69ms| 69ms | 0s | 0.000
| StatusStore.Get |  Avg| 67ms| 100ms | 33ms | 49.035
| |  P99| 496ms| 913ms | 417ms | 84.156
| StatusStore.GetByIds |  Avg| 182ms| 210ms | 28ms | 15.346
| |  P99| 1.679s| 2.017s | 338ms | 20.134
| StatusStore.SaveOrUpdate |  Avg| 24ms| 8ms | -16ms | -65.903
| |  P99| 439ms| 89ms | -350ms | -79.677
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 9ms| 11ms | 2ms | 22.809
| |  P99| 47ms| 207ms | 160ms | 338.624
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 7ms | -1ms | -13.316
| |  P99| 85ms| 91ms | 6ms | 7.032
| SystemStore.GetByName |  Avg| 4ms| 3ms | -1ms | -26.616
| |  P99| 54ms| 50ms | -4ms | -7.397
| TeamStore.AnalyticsTeamCount |  Avg| 177ms| 104ms | -73ms | -41.303
| |  P99| 249ms| 490ms | 241ms | 96.930
| TeamStore.Get |  Avg| 162ms| 162ms | 0s | 0.000
| |  P99| 1.683s| 1.69s | 7ms | 0.416
| TeamStore.GetActiveMemberCount |  Avg| 615ms| 395ms | -220ms | -35.756
| |  P99| 993ms| 975ms | -18ms | -1.812
| TeamStore.GetAllPage |  Avg| 115ms| 122ms | 7ms | 6.094
| |  P99| 916ms| 950ms | 34ms | 3.711
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 115ms| 118ms | 3ms | 2.617
| |  P99| 928ms| 943ms | 15ms | 1.616
| TeamStore.GetMember |  Avg| 10ms| 9ms | -1ms | -9.744
| |  P99| 225ms| 208ms | -17ms | -7.567
| TeamStore.GetTeamsByUserId |  Avg| 123ms| 117ms | -6ms | -4.894
| |  P99| 947ms| 925ms | -22ms | -2.323
| TeamStore.GetTeamsForUser |  Avg| 85ms| 93ms | 8ms | 9.402
| |  P99| 759ms| 808ms | 49ms | 6.453
| TeamStore.GetTotalMemberCount |  Avg| 445ms| 334ms | -111ms | -24.945
| |  P99| 980ms| 497ms | -483ms | -49.285
| TeamStore.SaveMember |  Avg| 208ms| 220ms | 12ms | 5.772
| |  P99| 954ms| 980ms | 26ms | 2.725
| ThreadStore.Get |  Avg| 243ms| 185ms | -58ms | -23.853
| |  P99| 2.495s| 985ms | -1.51s | -60.523
| ThreadStore.GetMembershipForUser |  Avg| 163ms| 169ms | 6ms | 3.684
| |  P99| 1.481s| 1.776s | 295ms | 19.918
| ThreadStore.GetTeamsUnreadForUser |  Avg| 148ms| 175ms | 27ms | 18.188
| |  P99| 1.78s| 2.074s | 294ms | 16.514
| ThreadStore.GetThreadFollowers |  Avg| 176ms| 173ms | -3ms | -1.705
| |  P99| 1.794s| 1.798s | 4ms | 0.223
| ThreadStore.GetThreadForUser |  Avg| 260ms| 259ms | -1ms | -0.385
| |  P99| 2.243s| 2.281s | 38ms | 1.694
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 193ms| 191ms | -2ms | -1.036
| |  P99| 1.959s| 2.031s | 72ms | 3.675
| ThreadStore.GetThreadsForUser |  Avg| 184ms| 186ms | 2ms | 1.088
| |  P99| 1.774s| 1.834s | 60ms | 3.383
| ThreadStore.GetTotalThreads |  Avg| 112ms| 123ms | 11ms | 9.804
| |  P99| 941ms| 977ms | 36ms | 3.827
| ThreadStore.GetTotalUnreadMentions |  Avg| 116ms| 127ms | 11ms | 9.521
| |  P99| 949ms| 991ms | 42ms | 4.424
| ThreadStore.GetTotalUnreadThreads |  Avg| 113ms| 124ms | 11ms | 9.702
| |  P99| 955ms| 977ms | 22ms | 2.303
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 114ms| 127ms | 13ms | 11.367
| |  P99| 957ms| 990ms | 33ms | 3.447
| ThreadStore.MaintainMembership |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 182ms| 185ms | 3ms | 1.649
| ThreadStore.MarkAllAsReadByChannels |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 94ms| 88ms | -6ms | -6.357
| ThreadStore.MarkAllAsReadByTeam |  Avg| 6ms| 5ms | -1ms | -17.371
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 8ms| 7ms | -1ms | -13.278
| |  P99| 78ms| 78ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 87ms | -1ms | -1.135
| TokenStore.Cleanup |  Avg| 14ms| 1ms | -13ms | -91.998
| |  P99| 25ms| 5ms | -20ms | -80.972
| UserAccessTokenStore.GetByToken |  Avg| 58ms| 49ms | -9ms | -15.641
| |  P99| 456ms| 244ms | -212ms | -46.466
| UserStore.AnalyticsActiveCount |  Avg| 652ms| 753ms | 101ms | 15.482
| |  P99| 995ms| 2.44s | 1.445s | 145.226
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 112ms| 186ms | 74ms | 66.076
| |  P99| 247ms| 490ms | 243ms | 98.275
| UserStore.AutocompleteUsersInChannel |  Avg| 734ms| 744ms | 10ms | 1.362
| |  P99| 2.5s| 2.495s | -5ms | -0.200
| UserStore.Count |  Avg| 345ms| 503ms | 158ms | 45.838
| |  P99| 979ms| 4.638s | 3.659s | 373.749
| UserStore.Get |  Avg| 66ms| 67ms | 1ms | 1.510
| |  P99| 827ms| 823ms | -4ms | -0.484
| UserStore.GetAllProfiles |  Avg| 90ms| 93ms | 3ms | 3.341
| |  P99| 881ms| 917ms | 36ms | 4.087
| UserStore.GetAllProfilesInChannel |  Avg| 1.14s| 1.157s | 17ms | 1.491
| |  P99| 2.496s| 2.982s | 486ms | 19.471
| UserStore.GetByUsername |  Avg| 192ms| 155ms | -37ms | -19.242
| |  P99| 1.938s| 987ms | -951ms | -49.084
| UserStore.GetForLogin |  Avg| 98ms| 107ms | 9ms | 9.199
| |  P99| 833ms| 897ms | 64ms | 7.680
| UserStore.GetMany |  Avg| 198ms| 178ms | -20ms | -10.123
| |  P99| 900ms| 905ms | 5ms | 0.556
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 238ms| 63ms | -175ms | -73.470
| |  P99| 249ms| 247ms | -2ms | -0.805
| UserStore.GetProfileByIds |  Avg| 86ms| 93ms | 7ms | 8.115
| |  P99| 936ms| 963ms | 27ms | 2.886
| UserStore.GetProfilesByUsernames |  Avg| 133ms| 130ms | -3ms | -2.249
| |  P99| 969ms| 980ms | 11ms | 1.135
| UserStore.GetProfilesInChannel |  Avg| 153ms| 153ms | 0s | 0.000
| |  P99| 490ms| 2.29s | 1.8s | 367.347
| UserStore.GetProfilesNotInChannel |  Avg| 208ms| 122ms | -86ms | -41.329
| |  P99| 495ms| 475ms | -20ms | -4.040
| UserStore.GetUnreadCount |  Avg| 147ms| 150ms | 3ms | 2.047
| |  P99| 1.325s| 1.413s | 88ms | 6.639
| UserStore.IsEmpty |  Avg| 53ms| 57ms | 4ms | 7.598
| |  P99| 478ms| 489ms | 11ms | 2.302
| UserStore.Save |  Avg| 84ms| 83ms | -1ms | -1.189
| |  P99| 332ms| 276ms | -56ms | -16.852
| UserStore.Search |  Avg| 407ms| 402ms | -5ms | -1.228
| |  P99| 2.174s| 2.205s | 31ms | 1.426
| UserStore.Update |  Avg| 16ms| 10ms | -6ms | -37.567
| |  P99| 252ms| 90ms | -162ms | -64.159
| UserStore.UpdateFailedPasswordAttempts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 75ms| 79ms | 4ms | 5.345
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 69ms| 68ms | -1ms | -1.441
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 61ms| 51ms | -10ms | -16.410
| UserTermsOfServiceStore.GetByUser |  Avg| 134ms| 140ms | 6ms | 4.484
| |  P99| 953ms| 1.029s | 76ms | 7.973
| WebhookStore.GetOutgoingByTeam |  Avg| 172ms| 175ms | 3ms | 1.740
| |  P99| 1.63s| 1.776s | 146ms | 8.955
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 2.303s| 2.456s | 153ms | 6.645
| | P99| 9.792s| 9.625s | -167ms | -1.706
| addTeamMember | Avg| 3.584s| 3.683s | 99ms | 2.762
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 601ms| 632ms | 31ms | 5.157
| | P99| 2.485s| 3.33s | 845ms | 34.004
| autocompleteUsers | Avg| 663ms| 673ms | 10ms | 1.508
| | P99| 2.486s| 2.497s | 11ms | 0.443
| channelMemberCountsByGroup | Avg| 15ms| 4ms | -11ms | -72.044
| | P99| 216ms| 45ms | -171ms | -79.061
| createCategoryForTeamForUser | Avg| 141ms| 416ms | 275ms | 195.667
| | P99| 493ms| 2.425s | 1.932s | 392.275
| createChannel | Avg| 3.289s| 1.808s | -1.481s | -45.032
| | P99| 9.75s| 9.45s | -300ms | -3.077
| createDirectChannel | Avg| 1.141s| 1.022s | -119ms | -10.434
| | P99| 4.827s| 4.75s | -77ms | -1.595
| createGroupChannel | Avg| 2.84s| 2.559s | -281ms | -9.893
| | P99| 9.57s| 9.913s | 343ms | 3.584
| createPost | Avg| 3.668s| 4.054s | 386ms | 10.522
| | P99| 10s| 10s | 0s | 0.000
| createUser | Avg| 368ms| 335ms | -33ms | -8.979
| | P99| 2.239s| 2.163s | -76ms | -3.395
| deleteDraft | Avg| 206ms| 203ms | -3ms | -1.453
| | P99| 1.996s| 2.01s | 14ms | 0.701
| deletePost | Avg| 966ms| 557ms | -409ms | -42.350
| | P99| 9.4s| 2.29s | -7.11s | -75.639
| followThreadByUser | Avg| 367ms| 489ms | 122ms | 33.234
| | P99| 980ms| 4.65s | 3.67s | 374.491
| getAllTeams | Avg| 122ms| 130ms | 8ms | 6.568
| | P99| 947ms| 975ms | 28ms | 2.956
| getAnalytics | Avg| 1.157s| 1.282s | 125ms | 10.803
| | P99| 2.485s| 2.478s | -7ms | -0.282
| getCategoriesForTeamForUser | Avg| 264ms| 295ms | 31ms | 11.729
| | P99| 2.251s| 2.299s | 48ms | 2.133
| getChannel | Avg| 499ms| 320ms | -179ms | -35.891
| | P99| 4.3s| 2.467s | -1.833s | -42.628
| getChannelMember | Avg| 171ms| 142ms | -29ms | -17.000
| | P99| 1.678s| 1.562s | -116ms | -6.915
| getChannelMembers | Avg| 107ms| 105ms | -2ms | -1.868
| | P99| 246ms| 247ms | 1ms | 0.406
| getChannelMembersForTeamForUser | Avg| 151ms| 158ms | 7ms | 4.636
| | P99| 1.263s| 1.552s | 289ms | 22.889
| getChannelMembersForUser | Avg| 221ms| 69ms | -152ms | -68.845
| | P99| 496ms| 246ms | -250ms | -50.378
| getChannelStats | Avg| 145ms| 125ms | -20ms | -13.818
| | P99| 2.023s| 1.951s | -72ms | -3.559
| getChannelUnread | Avg| 154ms| 142ms | -12ms | -7.799
| | P99| 1.272s| 1.371s | 99ms | 7.780
| getChannelsForTeamForUser | Avg| 164ms| 160ms | -4ms | -2.439
| | P99| 1.496s| 1.544s | 48ms | 3.208
| getChannelsForUser | Avg| 129ms| 133ms | 4ms | 3.106
| | P99| 958ms| 949ms | -9ms | -0.939
| getClientConfig | Avg| 29ms| 30ms | 1ms | 3.414
| | P99| 431ms| 442ms | 11ms | 2.554
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 188ms| 191ms | 3ms | 1.594
| | P99| 1.926s| 1.806s | -120ms | -6.232
| getFilePreview | Avg| 196ms| 187ms | -9ms | -4.586
| | P99| 1.375s| 1.446s | 71ms | 5.164
| getFileThumbnail | Avg| 191ms| 182ms | -9ms | -4.722
| | P99| 1.499s| 1.552s | 53ms | 3.536
| getFilteredUsersStats | Avg| 317ms| 891ms | 574ms | 181.047
| | P99| 985ms| 4.9s | 3.915s | 397.463
| getJobsByType | Avg| 263ms| 363ms | 100ms | 37.976
| | P99| 7.849s| 2.376s | -5.473s | -69.726
| getPostThread | Avg| 1.009s| 1.009s | 0s | 0.000
| | P99| 5.956s| 6.687s | 731ms | 12.272
| getPostsForChannel | Avg| 1.834s| 1.816s | -18ms | -0.981
| | P99| 10s| 10s | 0s | 0.000
| getPostsForChannelAroundLastUnread | Avg| 517ms| 592ms | 75ms | 14.495
| | P99| 4.171s| 4.592s | 421ms | 10.093
| getPreferences | Avg| 163ms| 166ms | 3ms | 1.835
| | P99| 1.137s| 1.382s | 245ms | 21.547
| getPrevTrialLicense | Avg| 261ms| 232ms | -29ms | -11.119
| | P99| 496ms| 493ms | -3ms | -0.605
| getProfileImage | Avg| 94ms| 90ms | -4ms | -4.262
| | P99| 478ms| 474ms | -4ms | -0.837
| getPublicChannelsForTeam | Avg| 193ms| 207ms | 14ms | 7.253
| | P99| 1.42s| 1.915s | 495ms | 34.862
| getRolesByNames | Avg| 130ms| 113ms | -17ms | -13.060
| | P99| 965ms| 945ms | -20ms | -2.073
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 13ms| 20ms | 7ms | 55.712
| | P99| 238ms| 386ms | 148ms | 62.087
| getTeamMembersForUser | Avg| 93ms| 102ms | 9ms | 9.717
| | P99| 845ms| 881ms | 36ms | 4.263
| getTeamStats | Avg| 852ms| 420ms | -432ms | -50.687
| | P99| 2.47s| 983ms | -1.487s | -60.202
| getTeamsForUser | Avg| 123ms| 118ms | -5ms | -4.064
| | P99| 948ms| 926ms | -22ms | -2.322
| getTeamsUnreadForUser | Avg| 186ms| 198ms | 12ms | 6.462
| | P99| 2.036s| 2.147s | 111ms | 5.451
| getThreadsForUser | Avg| 184ms| 192ms | 8ms | 4.346
| | P99| 1.959s| 2.021s | 62ms | 3.165
| getUser | Avg| 161ms| 166ms | 5ms | 3.110
| | P99| 1.087s| 1.566s | 479ms | 44.082
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 12ms| 14ms | 2ms | 16.398
| getUsers | Avg| 53ms| 54ms | 1ms | 1.871
| | P99| 696ms| 751ms | 55ms | 7.902
| getUsersByGroupChannelIds | Avg| 240ms| 123ms | -117ms | -48.695
| | P99| 249ms| 249ms | 0s | 0.000
| getUsersByIds | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 317ms| 339ms | 22ms | 6.937
| getUsersByNames | Avg| 135ms| 132ms | -3ms | -2.217
| | P99| 976ms| 986ms | 10ms | 1.024
| getWebappPlugins | Avg| 1ms| 0s | -1ms | -185.419
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 435ms| 449ms | 14ms | 3.219
| | P99| 2.61s| 3.084s | 474ms | 18.158
| logout | Avg| 236ms| 271ms | 35ms | 14.820
| | P99| 958ms| 970ms | 12ms | 1.253
| patchPost | Avg| 1.203s| 1.658s | 455ms | 37.829
| | P99| 8.067s| 10s | 1.933s | 23.963
| removeUserCustomStatus | Avg| 261ms| 207ms | -54ms | -20.705
| | P99| 1.045s| 983ms | -62ms | -5.934
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 527ms| 539ms | 12ms | 2.277
| | P99| 3.616s| 3.849s | 233ms | 6.443
| searchAllChannels | Avg| 3.947s| 4.067s | 120ms | 3.040
| | P99| 9.886s| 9.893s | 7ms | 0.071
| searchGroupChannels | Avg| 181ms| 189ms | 8ms | 4.424
| | P99| 1.762s| 1.876s | 114ms | 6.472
| searchPostsInTeam | Avg| 617ms| 556ms | -61ms | -9.892
| | P99| 7.25s| 4.891s | -2.359s | -32.539
| searchUsers | Avg| 413ms| 405ms | -8ms | -1.935
| | P99| 2.19s| 2.207s | 17ms | 0.776
| setPostReminder | Avg| 254ms| 894ms | 640ms | 252.145
| | P99| 495ms| 9.35s | 8.855s | 1788.081
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 492ms| 378ms | -114ms | -23.193
| | P99| 3.862s| 2.203s | -1.659s | -42.952
| updateCategoriesForTeamForUser | Avg| 979ms| 1.268s | 289ms | 29.535
| | P99| 2.465s| 8.001s | 5.536s | 224.584
| updatePreferences | Avg| 22ms| 21ms | -1ms | -4.521
| | P99| 237ms| 231ms | -6ms | -2.535
| updateReadStateAllThreadsByUser | Avg| 6ms| 5ms | -1ms | -17.063
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 1.379s| 1.322s | -57ms | -4.133
| | P99| 8.644s| 8.281s | -363ms | -4.199
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 428ms| 418ms | -10ms | -2.334
| | P99| 1.686s| 1.597s | -89ms | -5.280
| upsertDraft | Avg| 76ms| 74ms | -2ms | -2.620
| | P99| 979ms| 965ms | -14ms | -1.430
| viewChannel | Avg| 332ms| 332ms | 0s | 0.000
| | P99| 2.388s| 2.41s | 22ms | 0.921
