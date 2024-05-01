### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | avg | 2ms | 20ms | 18ms | 1066.76
| DraftStore.GetDraftsForUser | avg | 3ms | 28ms | 25ms | 810.37
| PluginStore.List | avg | 6ms | 15ms | 9ms | 149.35
| PostStore.AnalyticsPostCount | avg | 253ms | 607ms | 354ms | 140.05
| RetentionPolicyStore.GetCount | avg | 4ms | 9ms | 5ms | 117.69
| JobStore.GetAllByTypePage | avg | 9ms | 18ms | 9ms | 96.45
| JobStore.Save | avg | 6ms | 12ms | 6ms | 94.92
| TokenStore.Cleanup | avg | 25ms | 49ms | 24ms | 94.39
| JobStore.GetNewestJobByStatusesAndType | avg | 6ms | 11ms | 5ms | 89.99
| RoleStore.ChannelHigherScopedPermissions | avg | 11ms | 20ms | 9ms | 85.62
| JobStore.GetCountByStatusAndType | avg | 7ms | 12ms | 5ms | 72.04
| CommandWebhookStore.Cleanup | avg | 31ms | 53ms | 22ms | 70.75
| UserStore.GetProfilesInChannel | avg | 73ms | 122ms | 49ms | 66.89
| BotStore.Get | avg | 6ms | 10ms | 4ms | 65.92
| EmojiStore.GetMultipleByName | avg | 17ms | 28ms | 11ms | 63.80
| ChannelStore.CreateInitialSidebarCategories | avg | 36ms | 54ms | 18ms | 50.19
| PostStore.GetPostReminders | avg | 11ms | 16ms | 5ms | 46.49
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 30ms | 43ms | 13ms | 43.98
| ChannelStore.SearchGroupChannels | avg | 14ms | 20ms | 6ms | 42.28
| ChannelStore.Save | avg | 40ms | 50ms | 10ms | 25.00
| ComplianceStore.MessageExport | avg | 18ms | 22ms | 4ms | 22.79
| StatusStore.UpdateExpiredDNDStatuses | avg | 14ms | 17ms | 3ms | 20.76
| PostStore.GetPostReminderMetadata | avg | 11ms | 13ms | 2ms | 18.45
| ChannelStore.UpdateSidebarCategories | avg | 113ms | 132ms | 19ms | 16.76
| ClusterDiscoveryStore.SetLastPingAt | avg | 12ms | 14ms | 2ms | 16.59
| UserStore.GetRecentlyActiveUsersForTeam | avg | 75ms | 86ms | 11ms | 14.69
| ChannelStore.GetSidebarCategory | avg | 29ms | 33ms | 4ms | 13.64
| UserStore.Update | avg | 22ms | 24ms | 2ms | 9.05
| ChannelStore.GetPublicChannelsForTeam | avg | 30ms | 32ms | 2ms | 6.67
| TeamStore.GetTotalMemberCount | avg | 78ms | 83ms | 5ms | 6.39
| TeamStore.GetActiveMemberCount | avg | 82ms | 86ms | 4ms | 4.88
| ChannelStore.CreateDirectChannel | avg | 67ms | 69ms | 2ms | 3.00
| PostStore.SearchPostsForUser | avg | 253ms | 259ms | 6ms | 2.37
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.GetDraftsForUser | p99 | 5ms | 99ms | 94ms | 1898.99
| RetentionPolicyStore.GetAll | p99 | 5ms | 50ms | 45ms | 909.09
| ChannelStore.AutocompleteInTeamForSearch | p99 | 249ms | 1.382s | 1.133s | 454.32
| JobStore.GetAllByTypePage | p99 | 25ms | 96ms | 71ms | 287.45
| PluginStore.List | p99 | 45ms | 155ms | 110ms | 245.81
| JobStore.GetNewestJobByStatusesAndType | p99 | 48ms | 132ms | 84ms | 175.92
| PostStore.AnalyticsPostCount | p99 | 990ms | 2.47s | 1.48s | 149.49
| JobStore.Save | p99 | 65ms | 154ms | 89ms | 136.92
| PostStore.GetPostReminderMetadata | p99 | 93ms | 209ms | 116ms | 124.06
| ComplianceStore.MessageExport | p99 | 199ms | 422ms | 223ms | 112.33
| BotStore.Get | p99 | 46ms | 93ms | 47ms | 101.35
| RoleStore.ChannelHigherScopedPermissions | p99 | 48ms | 96ms | 48ms | 100.74
| UserStore.GetProfilesNotInChannel | p99 | 24ms | 46ms | 22ms | 90.06
| PostStore.SetPostReminder | p99 | 241ms | 395ms | 154ms | 64.03
| ClusterDiscoveryStore.SetLastPingAt | p99 | 147ms | 192ms | 45ms | 30.72
| JobStore.GetAllByStatus | p99 | 131ms | 164ms | 33ms | 25.20
| ChannelStore.GetMembersForUserWithPagination | p99 | 137ms | 169ms | 32ms | 23.28
| ChannelStore.SearchGroupChannels | p99 | 140ms | 171ms | 31ms | 22.20
| FileInfoStore.AttachToPost | p99 | 164ms | 184ms | 20ms | 12.23
| ChannelStore.GetPublicChannelsForTeam | p99 | 188ms | 209ms | 21ms | 11.14
| UserStore.IsEmpty | p99 | 37ms | 40ms | 3ms | 8.09
| ThreadStore.Get | p99 | 116ms | 125ms | 9ms | 7.77
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 201ms | 215ms | 14ms | 6.96
| UserStore.GetProfilesInChannel | p99 | 463ms | 494ms | 31ms | 6.69
| GroupStore.GetByName | p99 | 77ms | 81ms | 4ms | 5.18
| UserStore.AutocompleteUsersInChannel | p99 | 330ms | 347ms | 17ms | 5.16
| WebhookStore.GetOutgoingByTeam | p99 | 141ms | 147ms | 6ms | 4.25
| PostPersistentNotificationStore.Get | p99 | 78ms | 80ms | 2ms | 2.56
| ReactionStore.GetForPost | p99 | 86ms | 88ms | 2ms | 2.32
| FileInfoStore.GetForPost | p99 | 93ms | 95ms | 2ms | 2.16
| PostStore.GetPostReminders | p99 | 209ms | 212ms | 3ms | 1.43
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | avg | 2ms | 0s | -2ms | -122.53
| ChannelStore.GetMemberCountsByGroup | avg | 10ms | 0s | -10ms | -96.87
| ProductNoticesStore.GetViews | avg | 32ms | 2ms | -30ms | -94.11
| BotStore.Save | avg | 2ms | 0s | -2ms | -93.56
| DraftStore.Get | avg | 24ms | 2ms | -22ms | -92.41
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 19ms | 2ms | -17ms | -90.22
| ThreadStore.MarkAllAsReadByTeam | avg | 26ms | 3ms | -23ms | -90.00
| SessionStore.GetSessionsExpired | avg | 16ms | 4ms | -12ms | -76.58
| LicenseStore.GetAll | avg | 12ms | 5ms | -7ms | -56.73
| ChannelStore.GetMembers | avg | 43ms | 20ms | -23ms | -53.30
| JobStore.UpdateStatus | avg | 11ms | 5ms | -6ms | -52.19
| ChannelStore.CreateSidebarCategory | avg | 104ms | 51ms | -53ms | -50.83
| SessionStore.Remove | avg | 14ms | 7ms | -7ms | -49.86
| UserStore.AnalyticsGetInactiveUsersCount | avg | 8ms | 4ms | -4ms | -49.70
| ChannelStore.GetByNameIncludeDeleted | avg | 6ms | 3ms | -3ms | -47.13
| TeamStore.AnalyticsTeamCount | avg | 15ms | 8ms | -7ms | -46.53
| PostPersistentNotificationStore.DeleteExpired | avg | 12ms | 7ms | -5ms | -43.12
| UserStore.GetMany | avg | 10ms | 6ms | -4ms | -40.22
| UserStore.Count | avg | 39ms | 25ms | -14ms | -35.87
| JobStore.UpdateStatusOptimistically | avg | 11ms | 7ms | -4ms | -35.47
| JobStore.Get | avg | 20ms | 14ms | -6ms | -30.10
| ChannelStore.GetMembersForUserWithPagination | avg | 27ms | 20ms | -7ms | -25.86
| DraftStore.Delete | avg | 8ms | 6ms | -2ms | -24.11
| ChannelStore.AnalyticsTypeCount | avg | 23ms | 18ms | -5ms | -21.42
| JobStore.UpdateOptimistically | avg | 14ms | 11ms | -3ms | -21.20
| PostStore.Delete | avg | 40ms | 32ms | -8ms | -20.22
| ChannelStore.GetTeamChannels | avg | 50ms | 40ms | -10ms | -20.17
| LinkMetadataStore.Save | avg | 11ms | 9ms | -2ms | -18.85
| UserStore.AnalyticsActiveCount | avg | 53ms | 44ms | -9ms | -17.13
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 12ms | 10ms | -2ms | -17.09
| UserAccessTokenStore.GetByToken | avg | 12ms | 10ms | -2ms | -16.95
| PreferenceStore.DeleteCategoryAndName | avg | 12ms | 10ms | -2ms | -16.77
| PostStore.Update | avg | 31ms | 26ms | -5ms | -16.29
| StatusStore.GetByIds | avg | 13ms | 11ms | -2ms | -15.14
| FileInfoStore.SetContent | avg | 22ms | 19ms | -3ms | -13.34
| ChannelStore.AutocompleteInTeamForSearch | avg | 96ms | 84ms | -12ms | -12.52
| ProductNoticesStore.ClearOldNotices | avg | 41ms | 36ms | -5ms | -12.22
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 32ms | 30ms | -2ms | -6.29
| PostStore.SetPostReminder | avg | 37ms | 35ms | -2ms | -5.43
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 127ms | 121ms | -6ms | -4.71
| UserStore.GetAllProfilesInChannel | avg | 452ms | 434ms | -18ms | -3.98
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 90ms | 0s | -90ms | -100.28
| ProductNoticesStore.GetViews | p99 | 99ms | 5ms | -94ms | -95.43
| ThreadStore.MarkAllAsReadByTeam | p99 | 98ms | 5ms | -93ms | -94.90
| DraftStore.Get | p99 | 98ms | 5ms | -93ms | -94.90
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 49ms | 5ms | -44ms | -89.34
| JobStore.UpdateStatus | p99 | 145ms | 24ms | -121ms | -83.45
| PostPersistentNotificationStore.DeleteExpired | p99 | 390ms | 80ms | -310ms | -79.49
| UserStore.Count | p99 | 375ms | 91ms | -284ms | -75.73
| SessionStore.GetSessionsExpired | p99 | 94ms | 24ms | -70ms | -74.07
| TeamStore.AnalyticsTeamCount | p99 | 96ms | 25ms | -71ms | -73.95
| JobStore.UpdateStatusOptimistically | p99 | 197ms | 68ms | -129ms | -65.57
| CommandWebhookStore.Cleanup | p99 | 244ms | 99ms | -145ms | -59.43
| ChannelStore.GetMembers | p99 | 242ms | 98ms | -144ms | -59.38
| StatusStore.UpdateExpiredDNDStatuses | p99 | 230ms | 96ms | -134ms | -58.32
| PostStore.Delete | p99 | 237ms | 99ms | -138ms | -58.17
| ChannelStore.UpdateSidebarCategories | p99 | 1.705s | 770ms | -935ms | -54.84
| SessionStore.Remove | p99 | 93ms | 44ms | -49ms | -52.55
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 49ms | 24ms | -25ms | -51.28
| LicenseStore.GetAll | p99 | 93ms | 46ms | -47ms | -50.54
| ChannelStore.GetByNameIncludeDeleted | p99 | 10ms | 5ms | -5ms | -50.22
| ChannelStore.AnalyticsTypeCount | p99 | 97ms | 49ms | -48ms | -49.72
| ChannelStore.CreateSidebarCategory | p99 | 485ms | 244ms | -241ms | -49.69
| PreferenceStore.DeleteCategoryAndName | p99 | 92ms | 48ms | -44ms | -48.09
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 92ms | 49ms | -43ms | -46.99
| JobStore.UpdateOptimistically | p99 | 185ms | 98ms | -87ms | -46.98
| PostAcknowledgementStore.GetForPost | p99 | 91ms | 49ms | -42ms | -46.41
| UserStore.GetMany | p99 | 82ms | 44ms | -38ms | -46.34
| UserAccessTokenStore.GetByToken | p99 | 139ms | 78ms | -61ms | -43.88
| UserStore.GetByUsername | p99 | 167ms | 96ms | -71ms | -42.54
| ChannelStore.GetSidebarCategory | p99 | 380ms | 228ms | -152ms | -40.00
| LinkMetadataStore.Save | p99 | 139ms | 88ms | -51ms | -36.69
| StatusStore.SaveOrUpdate | p99 | 1.398s | 990ms | -408ms | -29.19
| ChannelStore.Get | p99 | 131ms | 97ms | -34ms | -25.91
| PostStore.GetPostsAfter | p99 | 116ms | 88ms | -28ms | -24.22
| JobStore.Get | p99 | 210ms | 161ms | -49ms | -23.30
| ChannelStore.GetMemberForPost | p99 | 156ms | 122ms | -34ms | -21.83
| PostStore.GetEtag | p99 | 123ms | 100ms | -23ms | -18.77
| PostStore.GetPostsBefore | p99 | 130ms | 106ms | -24ms | -18.52
| ThreadStore.GetTeamsUnreadForUser | p99 | 142ms | 117ms | -25ms | -17.57
| PostStore.Update | p99 | 280ms | 231ms | -49ms | -17.50
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 64ms | 53ms | -11ms | -17.10
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 98ms | 84ms | -14ms | -14.28
| ChannelStore.GetFileCount | p99 | 113ms | 97ms | -16ms | -14.19
| UserStore.GetAllProfiles | p99 | 64ms | 55ms | -9ms | -14.04
| ChannelStore.GetChannelUnread | p99 | 113ms | 98ms | -15ms | -13.32
| ChannelStore.GetPinnedPostCount | p99 | 111ms | 97ms | -14ms | -12.62
| PostStore.Save | p99 | 335ms | 293ms | -42ms | -12.54
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 77ms | 68ms | -9ms | -11.72
| PluginStore.SetWithOptions | p99 | 108ms | 96ms | -12ms | -11.12
| ChannelStore.GetChannels | p99 | 111ms | 99ms | -12ms | -10.84
| ChannelStore.Save | p99 | 447ms | 404ms | -43ms | -9.63
| FileInfoStore.SetContent | p99 | 225ms | 204ms | -21ms | -9.33
| TeamStore.GetMember | p99 | 45ms | 41ms | -4ms | -8.98
| UserStore.UpdateUpdateAt | p99 | 69ms | 63ms | -6ms | -8.70
| EmojiStore.GetByName | p99 | 96ms | 88ms | -8ms | -8.37
| ChannelStore.GetTeamChannels | p99 | 244ms | 224ms | -20ms | -8.20
| ProductNoticesStore.View | p99 | 709ms | 653ms | -56ms | -7.90
| ChannelStore.GetChannelsByUser | p99 | 103ms | 95ms | -8ms | -7.80
| ThreadStore.GetThreadsForUser | p99 | 131ms | 121ms | -10ms | -7.62
| ThreadStore.MarkAllAsReadByChannels | p99 | 98ms | 91ms | -7ms | -7.11
| UserStore.UpdateFailedPasswordAttempts | p99 | 85ms | 79ms | -6ms | -7.06
| StatusStore.GetByIds | p99 | 128ms | 119ms | -9ms | -7.06
| SessionStore.Save | p99 | 143ms | 133ms | -10ms | -7.00
| UserStore.GetProfileByIds | p99 | 107ms | 100ms | -7ms | -6.54
| PostAcknowledgementStore.GetForPosts | p99 | 177ms | 166ms | -11ms | -6.20
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 469ms | 441ms | -28ms | -5.97
| FileInfoStore.Get | p99 | 105ms | 99ms | -6ms | -5.71
| PreferenceStore.Get | p99 | 105ms | 99ms | -6ms | -5.69
| StatusStore.UpdateLastActivityAt | p99 | 89ms | 84ms | -5ms | -5.63
| PostPriorityStore.GetForPosts | p99 | 181ms | 171ms | -10ms | -5.51
| TeamStore.Get | p99 | 91ms | 86ms | -5ms | -5.50
| UserStore.GetProfilesByUsernames | p99 | 114ms | 108ms | -6ms | -5.25
| UserStore.Update | p99 | 237ms | 225ms | -12ms | -5.07
| SystemStore.GetByName | p99 | 80ms | 76ms | -4ms | -5.01
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 86ms | 82ms | -4ms | -4.66
| UserStore.UpdateLastLogin | p99 | 66ms | 63ms | -3ms | -4.55
| ThreadStore.GetThreadFollowers | p99 | 88ms | 84ms | -4ms | -4.53
| TeamStore.GetTeamsByUserId | p99 | 89ms | 85ms | -4ms | -4.48
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 90ms | 86ms | -4ms | -4.42
| ChannelStore.CreateInitialSidebarCategories | p99 | 439ms | 420ms | -19ms | -4.33
| PostStore.GetSingle | p99 | 93ms | 89ms | -4ms | -4.30
| ChannelStore.GetGuestCount | p99 | 94ms | 90ms | -4ms | -4.26
| LinkMetadataStore.Get | p99 | 95ms | 91ms | -4ms | -4.23
| PostStore.GetPostIdAfterTime | p99 | 71ms | 68ms | -3ms | -4.22
| ChannelStore.GetMemberCount | p99 | 200ms | 192ms | -8ms | -4.00
| ThreadStore.GetThreadUnreadReplyCount | p99 | 101ms | 97ms | -4ms | -3.96
| UserTermsOfServiceStore.GetByUser | p99 | 81ms | 78ms | -3ms | -3.72
| UserStore.GetAllProfilesInChannel | p99 | 2.277s | 2.193s | -84ms | -3.69
| PostPersistentNotificationStore.GetSingle | p99 | 83ms | 80ms | -3ms | -3.61
| ThreadStore.MaintainMembership | p99 | 223ms | 215ms | -8ms | -3.58
| ChannelStore.IncrementMentionCount | p99 | 88ms | 85ms | -3ms | -3.40
| ThreadStore.UpdateMembership | p99 | 89ms | 86ms | -3ms | -3.39
| SessionStore.UpdateLastActivityAt | p99 | 89ms | 86ms | -3ms | -3.35
| UserStore.GetUnreadCount | p99 | 90ms | 87ms | -3ms | -3.34
| ChannelStore.UpdateLastViewedAt | p99 | 93ms | 90ms | -3ms | -3.22
| GroupStore.GetGroups | p99 | 93ms | 90ms | -3ms | -3.21
| PreferenceStore.GetAll | p99 | 93ms | 90ms | -3ms | -3.21
| ChannelStore.GetMember | p99 | 95ms | 92ms | -3ms | -3.14
| JobStore.GetCountByStatusAndType | p99 | 96ms | 93ms | -3ms | -3.12
| ThreadStore.GetMembershipForUser | p99 | 96ms | 93ms | -3ms | -3.11
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 97ms | 94ms | -3ms | -3.09
| SessionStore.GetLRUSessions | p99 | 75ms | 73ms | -2ms | -2.68
| PostStore.Get | p99 | 225ms | 219ms | -6ms | -2.67
| AuditStore.Save | p99 | 81ms | 79ms | -2ms | -2.46
| PostStore.GetPostsSince | p99 | 210ms | 205ms | -5ms | -2.39
| TeamStore.GetAllPage | p99 | 87ms | 85ms | -2ms | -2.30
| ThreadStore.GetTotalUnreadThreads | p99 | 88ms | 86ms | -2ms | -2.28
| ChannelStore.GetAllChannelMembersForUser | p99 | 93ms | 91ms | -2ms | -2.14
| PostStore.GetPostIdBeforeTime | p99 | 93ms | 91ms | -2ms | -2.14
| PostPriorityStore.GetForPost | p99 | 94ms | 92ms | -2ms | -2.12
| ChannelStore.GetMembersForUser | p99 | 100ms | 98ms | -2ms | -2.01
| SessionStore.Get | p99 | 190ms | 187ms | -3ms | -1.58
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 362ms | 358ms | -4ms | -1.11
| ThreadStore.GetThreadForUser | p99 | 190ms | 188ms | -2ms | -1.05
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getJobsByType | avg | 9ms | 19ms | 10ms | 105.40
| upsertDraft | avg | 9ms | 15ms | 6ms | 64.83
| getCategoriesForTeamForUser | avg | 30ms | 43ms | 13ms | 43.30
| searchGroupChannels | avg | 14ms | 20ms | 6ms | 41.70
| logout | avg | 161ms | 191ms | 30ms | 18.62
| updateCategoriesForTeamForUser | avg | 184ms | 206ms | 22ms | 11.99
| getTeamStats | avg | 89ms | 98ms | 9ms | 10.12
| createGroupChannel | avg | 690ms | 759ms | 69ms | 10.00
| getPublicChannelsForTeam | avg | 32ms | 34ms | 2ms | 6.31
| searchPostsInTeam | avg | 279ms | 286ms | 7ms | 2.51
| removeUserCustomStatus | avg | 303ms | 310ms | 7ms | 2.31
| addTeamMember | avg | 1.271s | 1.291s | 20ms | 1.57
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 249ms | 1.382s | 1.133s | 454.32
| getJobsByType | p99 | 25ms | 96ms | 71ms | 287.45
| getClientLicense | p99 | 10ms | 24ms | 14ms | 145.83
| upsertDraft | p99 | 25ms | 49ms | 24ms | 97.17
| setPostReminder | p99 | 476ms | 790ms | 314ms | 65.93
| createGroupChannel | p99 | 3.025s | 4.33s | 1.305s | 43.14
| searchGroupChannels | p99 | 145ms | 174ms | 29ms | 20.05
| getChannel | p99 | 194ms | 217ms | 23ms | 11.86
| removeUserCustomStatus | p99 | 1.7s | 1.87s | 170ms | 10.00
| autocompleteUsers | p99 | 265ms | 287ms | 22ms | 8.31
| getPublicChannelsForTeam | p99 | 196ms | 209ms | 13ms | 6.63
| updateCategoriesForTeamForUser | p99 | 1.705s | 1.81s | 105ms | 6.16
| createDirectChannel | p99 | 2.342s | 2.428s | 86ms | 3.67
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 12ms | 0s | -12ms | -100.87
| getSelfHostedProducts | avg | 137ms | 0s | -137ms | -100.01
| getProductNotices | avg | 33ms | 2ms | -31ms | -95.23
| getPoliciesCount | avg | 18ms | 1ms | -17ms | -95.05
| updateReadStateAllThreadsByUser | avg | 26ms | 3ms | -23ms | -89.59
| deleteDraft | avg | 23ms | 4ms | -19ms | -84.12
| getGroupsAssociatedToChannelsByTeam | avg | 11ms | 2ms | -9ms | -80.86
| getFilteredUsersStats | avg | 82ms | 25ms | -57ms | -69.84
| getGroups | avg | 12ms | 4ms | -8ms | -68.00
| getChannelMembersForUser | avg | 38ms | 13ms | -25ms | -65.51
| getPrevTrialLicense | avg | 12ms | 5ms | -7ms | -58.29
| getChannelMembers | avg | 44ms | 21ms | -23ms | -52.20
| createCategoryForTeamForUser | avg | 120ms | 69ms | -51ms | -42.63
| getAnalytics | avg | 95ms | 56ms | -39ms | -41.21
| createChannel | avg | 869ms | 525ms | -344ms | -39.57
| deletePost | avg | 76ms | 54ms | -22ms | -29.12
| followThreadByUser | avg | 53ms | 44ms | -9ms | -17.13
| handleCheckCWSConnection | avg | 69ms | 58ms | -11ms | -15.95
| unfollowThreadByUser | avg | 57ms | 49ms | -8ms | -14.07
| autocompleteChannelsForTeamForSearch | avg | 96ms | 84ms | -12ms | -12.51
| getLicenseSelfServeStatus | avg | 100ms | 90ms | -10ms | -9.97
| addChannelMember | avg | 458ms | 415ms | -43ms | -9.40
| patchPost | avg | 166ms | 151ms | -15ms | -9.04
| saveReaction | avg | 37ms | 34ms | -3ms | -8.21
| createDirectChannel | avg | 481ms | 442ms | -39ms | -8.11
| setPostReminder | avg | 91ms | 85ms | -6ms | -6.59
| getPostsForChannel | avg | 101ms | 95ms | -6ms | -5.94
| getProfileImage | avg | 92ms | 88ms | -4ms | -4.34
| login | avg | 165ms | 158ms | -7ms | -4.23
| getPostThread | avg | 56ms | 54ms | -2ms | -3.55
| uploadFileStream | avg | 483ms | 466ms | -17ms | -3.52
| createPost | avg | 831ms | 807ms | -24ms | -2.89
| updateReadStateThreadByUser | avg | 130ms | 128ms | -2ms | -1.54
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUserLimits | p99 | 5ms | 0s | -5ms | -101.01
| channelMemberCountsByGroup | p99 | 90ms | 0s | -90ms | -100.28
| getSelfHostedProducts | p99 | 495ms | 0s | -495ms | -100.00
| getProductNotices | p99 | 99ms | 5ms | -94ms | -95.43
| updateReadStateAllThreadsByUser | p99 | 98ms | 5ms | -93ms | -94.90
| deleteDraft | p99 | 97ms | 5ms | -92ms | -94.36
| getChannelMembersForUser | p99 | 236ms | 25ms | -211ms | -89.22
| getGroupsAssociatedToChannelsByTeam | p99 | 25ms | 5ms | -20ms | -80.84
| getPoliciesCount | p99 | 25ms | 5ms | -20ms | -80.48
| getFilteredUsersStats | p99 | 247ms | 50ms | -197ms | -79.76
| getChannelMembers | p99 | 242ms | 98ms | -144ms | -59.38
| getRolesByNames | p99 | 24ms | 10ms | -14ms | -58.46
| getGroups | p99 | 49ms | 24ms | -25ms | -51.41
| getAnalytics | p99 | 468ms | 228ms | -240ms | -51.32
| createCategoryForTeamForUser | p99 | 492ms | 244ms | -248ms | -50.36
| deletePost | p99 | 479ms | 243ms | -236ms | -49.29
| followThreadByUser | p99 | 455ms | 240ms | -215ms | -47.25
| logout | p99 | 875ms | 491ms | -384ms | -43.89
| updatePreferences | p99 | 361ms | 262ms | -99ms | -27.46
| getTeamMember | p99 | 130ms | 99ms | -31ms | -23.88
| unfollowThreadByUser | p99 | 420ms | 321ms | -99ms | -23.54
| getChannelsForUser | p99 | 122ms | 97ms | -25ms | -20.41
| login | p99 | 1.44s | 1.194s | -246ms | -17.08
| patchPost | p99 | 1.43s | 1.21s | -220ms | -15.38
| getChannelMembersForTeamForUser | p99 | 117ms | 101ms | -16ms | -13.65
| getChannelUnread | p99 | 144ms | 125ms | -19ms | -13.21
| getFilePreview | p99 | 339ms | 297ms | -42ms | -12.40
| addTeamMember | p99 | 7.222s | 6.363s | -859ms | -11.89
| saveReaction | p99 | 265ms | 241ms | -24ms | -9.06
| getTeamMembersForUser | p99 | 119ms | 109ms | -10ms | -8.37
| getAllTeams | p99 | 106ms | 98ms | -8ms | -7.53
| getChannelsForTeamForUser | p99 | 134ms | 124ms | -10ms | -7.48
| getTeamsUnreadForUser | p99 | 202ms | 189ms | -13ms | -6.44
| updateReadStateThreadByUser | p99 | 887ms | 831ms | -56ms | -6.31
| getThreadsForUser | p99 | 154ms | 145ms | -9ms | -5.85
| createPost | p99 | 4.629s | 4.375s | -254ms | -5.49
| viewChannel | p99 | 414ms | 393ms | -21ms | -5.07
| getPostsForChannel | p99 | 981ms | 933ms | -48ms | -4.89
| getPostThread | p99 | 459ms | 437ms | -22ms | -4.80
| addChannelMember | p99 | 2.233s | 2.132s | -101ms | -4.52
| getTeamsForUser | p99 | 91ms | 87ms | -4ms | -4.42
| getPreferences | p99 | 97ms | 93ms | -4ms | -4.13
| getPostsForChannelAroundLastUnread | p99 | 459ms | 443ms | -16ms | -3.49
| getUsersByNames | p99 | 128ms | 124ms | -4ms | -3.11
| uploadFileStream | p99 | 2.142s | 2.092s | -50ms | -2.33
| getUser | p99 | 217ms | 212ms | -5ms | -2.30
| getClientConfig | p99 | 229ms | 224ms | -5ms | -2.18
| getChannelMember | p99 | 230ms | 225ms | -5ms | -2.17
| getProfileImage | p99 | 489ms | 479ms | -10ms | -2.04
| getFileThumbnail | p99 | 251ms | 246ms | -5ms | -1.99
| createUser | p99 | 1.556s | 1.527s | -29ms | -1.86
| createChannel | p99 | 2.44s | 2.415s | -25ms | -1.02
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 81ms| 79ms | -2ms | -2.462
| BotStore.Get |  Avg| 6ms| 10ms | 4ms | 65.923
| |  P99| 46ms| 93ms | 47ms | 101.348
| BotStore.Save |  Avg| 2ms| 0s | -2ms | -93.565
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 127ms| 121ms | -6ms | -4.711
| |  P99| 469ms| 441ms | -28ms | -5.969
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 6ms| 5ms | -1ms | -18.075
| |  P99| 64ms| 53ms | -11ms | -17.098
| ChannelStore.AnalyticsTypeCount |  Avg| 23ms| 18ms | -5ms | -21.424
| |  P99| 97ms| 49ms | -48ms | -49.720
| ChannelStore.Autocomplete |  Avg| 60ms| 59ms | -1ms | -1.665
| |  P99| 239ms| 239ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 96ms| 84ms | -12ms | -12.518
| |  P99| 249ms| 1.382s | 1.133s | 454.325
| ChannelStore.CreateDirectChannel |  Avg| 67ms| 69ms | 2ms | 2.996
| |  P99| 474ms| 478ms | 4ms | 0.843
| ChannelStore.CreateInitialSidebarCategories |  Avg| 36ms| 54ms | 18ms | 50.188
| |  P99| 439ms| 420ms | -19ms | -4.330
| ChannelStore.CreateSidebarCategory |  Avg| 104ms| 51ms | -53ms | -50.826
| |  P99| 485ms| 244ms | -241ms | -49.691
| ChannelStore.Get |  Avg| 12ms| 11ms | -1ms | -8.138
| |  P99| 131ms| 97ms | -34ms | -25.910
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 29ms| 28ms | -1ms | -3.466
| |  P99| 201ms| 215ms | 14ms | 6.964
| ChannelStore.GetAllChannelMembersForUser |  Avg| 12ms| 11ms | -1ms | -8.314
| |  P99| 93ms| 91ms | -2ms | -2.145
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 32ms| 30ms | -2ms | -6.286
| |  P99| 362ms| 358ms | -4ms | -1.106
| ChannelStore.GetByName |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 89ms| 88ms | -1ms | -1.127
| ChannelStore.GetByNameIncludeDeleted |  Avg| 6ms| 3ms | -3ms | -47.130
| |  P99| 10ms| 5ms | -5ms | -50.224
| ChannelStore.GetChannelUnread |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 113ms| 98ms | -15ms | -13.322
| ChannelStore.GetChannels |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 111ms| 99ms | -12ms | -10.841
| ChannelStore.GetChannelsByUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 103ms| 95ms | -8ms | -7.803
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 97ms| 94ms | -3ms | -3.088
| ChannelStore.GetFileCount |  Avg| 12ms| 11ms | -1ms | -8.327
| |  P99| 113ms| 97ms | -16ms | -14.193
| ChannelStore.GetGuestCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 94ms| 90ms | -4ms | -4.263
| ChannelStore.GetMember |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 95ms| 92ms | -3ms | -3.143
| ChannelStore.GetMemberCount |  Avg| 35ms| 34ms | -1ms | -2.886
| |  P99| 200ms| 192ms | -8ms | -4.000
| ChannelStore.GetMemberCountsByGroup |  Avg| 10ms| 0s | -10ms | -96.869
| |  P99| 90ms| 0s | -90ms | -100.279
| ChannelStore.GetMemberForPost |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 156ms| 122ms | -34ms | -21.829
| ChannelStore.GetMemberLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 78ms| 79ms | 1ms | 1.286
| ChannelStore.GetMembers |  Avg| 43ms| 20ms | -23ms | -53.297
| |  P99| 242ms| 98ms | -144ms | -59.382
| ChannelStore.GetMembersForUser |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 100ms| 98ms | -2ms | -2.010
| ChannelStore.GetMembersForUserWithPagination |  Avg| 27ms| 20ms | -7ms | -25.863
| |  P99| 137ms| 169ms | 32ms | 23.279
| ChannelStore.GetPinnedPostCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 111ms| 97ms | -14ms | -12.623
| ChannelStore.GetPublicChannelsForTeam |  Avg| 30ms| 32ms | 2ms | 6.669
| |  P99| 188ms| 209ms | 21ms | 11.143
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 30ms| 43ms | 13ms | 43.985
| |  P99| 232ms| 233ms | 1ms | 0.432
| ChannelStore.GetSidebarCategory |  Avg| 29ms| 33ms | 4ms | 13.640
| |  P99| 380ms| 228ms | -152ms | -39.999
| ChannelStore.GetTeamChannels |  Avg| 50ms| 40ms | -10ms | -20.170
| |  P99| 244ms| 224ms | -20ms | -8.197
| ChannelStore.IncrementMentionCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 88ms| 85ms | -3ms | -3.398
| ChannelStore.Save |  Avg| 40ms| 50ms | 10ms | 24.996
| |  P99| 447ms| 404ms | -43ms | -9.627
| ChannelStore.SaveMember |  Avg| 54ms| 54ms | 0s | 0.000
| |  P99| 441ms| 438ms | -3ms | -0.681
| ChannelStore.SearchGroupChannels |  Avg| 14ms| 20ms | 6ms | 42.283
| |  P99| 140ms| 171ms | 31ms | 22.203
| ChannelStore.UpdateLastViewedAt |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 93ms| 90ms | -3ms | -3.222
| ChannelStore.UpdateSidebarCategories |  Avg| 113ms| 132ms | 19ms | 16.758
| |  P99| 1.705s| 770ms | -935ms | -54.836
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 98ms| 84ms | -14ms | -14.284
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 12ms| 14ms | 2ms | 16.590
| |  P99| 147ms| 192ms | 45ms | 30.716
| CommandWebhookStore.Cleanup |  Avg| 31ms| 53ms | 22ms | 70.753
| |  P99| 244ms| 99ms | -145ms | -59.426
| ComplianceStore.MessageExport |  Avg| 18ms| 22ms | 4ms | 22.790
| |  P99| 199ms| 422ms | 223ms | 112.327
| DraftStore.Delete |  Avg| 8ms| 6ms | -2ms | -24.112
| |  P99| 25ms| 24ms | -1ms | -4.049
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 12ms| 10ms | -2ms | -17.090
| |  P99| 92ms| 49ms | -43ms | -46.994
| DraftStore.Get |  Avg| 24ms| 2ms | -22ms | -92.405
| |  P99| 98ms| 5ms | -93ms | -94.898
| DraftStore.GetDraftsForUser |  Avg| 3ms| 28ms | 25ms | 810.375
| |  P99| 5ms| 99ms | 94ms | 1898.990
| EmojiStore.GetByName |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 96ms| 88ms | -8ms | -8.375
| EmojiStore.GetMultipleByName |  Avg| 17ms| 28ms | 11ms | 63.796
| |  P99| 97ms| 98ms | 1ms | 1.031
| FileInfoStore.AttachToPost |  Avg| 15ms| 16ms | 1ms | 6.564
| |  P99| 164ms| 184ms | 20ms | 12.227
| FileInfoStore.Get |  Avg| 11ms| 10ms | -1ms | -9.401
| |  P99| 105ms| 99ms | -6ms | -5.714
| FileInfoStore.GetForPost |  Avg| 9ms| 10ms | 1ms | 10.803
| |  P99| 93ms| 95ms | 2ms | 2.159
| FileInfoStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 99ms| 98ms | -1ms | -1.008
| FileInfoStore.SetContent |  Avg| 22ms| 19ms | -3ms | -13.340
| |  P99| 225ms| 204ms | -21ms | -9.329
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 6ms| 5ms | -1ms | -17.770
| |  P99| 77ms| 68ms | -9ms | -11.721
| GroupStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 77ms| 81ms | 4ms | 5.181
| GroupStore.GetGroups |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 93ms| 90ms | -3ms | -3.212
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 19ms| 2ms | -17ms | -90.221
| |  P99| 49ms| 5ms | -44ms | -89.339
| JobStore.Get |  Avg| 20ms| 14ms | -6ms | -30.095
| |  P99| 210ms| 161ms | -49ms | -23.300
| JobStore.GetAllByStatus |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 131ms| 164ms | 33ms | 25.197
| JobStore.GetAllByTypePage |  Avg| 9ms| 18ms | 9ms | 96.445
| |  P99| 25ms| 96ms | 71ms | 287.448
| JobStore.GetCountByStatusAndType |  Avg| 7ms| 12ms | 5ms | 72.043
| |  P99| 96ms| 93ms | -3ms | -3.125
| JobStore.GetNewestJobByStatusesAndType |  Avg| 6ms| 11ms | 5ms | 89.993
| |  P99| 48ms| 132ms | 84ms | 175.916
| JobStore.Save |  Avg| 6ms| 12ms | 6ms | 94.923
| |  P99| 65ms| 154ms | 89ms | 136.923
| JobStore.UpdateOptimistically |  Avg| 14ms| 11ms | -3ms | -21.204
| |  P99| 185ms| 98ms | -87ms | -46.980
| JobStore.UpdateStatus |  Avg| 11ms| 5ms | -6ms | -52.189
| |  P99| 145ms| 24ms | -121ms | -83.448
| JobStore.UpdateStatusOptimistically |  Avg| 11ms| 7ms | -4ms | -35.474
| |  P99| 197ms| 68ms | -129ms | -65.565
| LicenseStore.GetAll |  Avg| 12ms| 5ms | -7ms | -56.732
| |  P99| 93ms| 46ms | -47ms | -50.537
| LinkMetadataStore.Get |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 95ms| 91ms | -4ms | -4.231
| LinkMetadataStore.Save |  Avg| 11ms| 9ms | -2ms | -18.847
| |  P99| 139ms| 88ms | -51ms | -36.689
| PluginStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 54ms| 54ms | 0s | 0.000
| PluginStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PluginStore.List |  Avg| 6ms| 15ms | 9ms | 149.353
| |  P99| 45ms| 155ms | 110ms | 245.810
| PluginStore.SetWithOptions |  Avg| 9ms| 8ms | -1ms | -10.649
| |  P99| 108ms| 96ms | -12ms | -11.119
| PostAcknowledgementStore.GetForPost |  Avg| 8ms| 7ms | -1ms | -12.250
| |  P99| 91ms| 49ms | -42ms | -46.409
| PostAcknowledgementStore.GetForPosts |  Avg| 13ms| 12ms | -1ms | -7.924
| |  P99| 177ms| 166ms | -11ms | -6.200
| PostPersistentNotificationStore.DeleteExpired |  Avg| 12ms| 7ms | -5ms | -43.124
| |  P99| 390ms| 80ms | -310ms | -79.487
| PostPersistentNotificationStore.Get |  Avg| 6ms| 5ms | -1ms | -16.472
| |  P99| 78ms| 80ms | 2ms | 2.564
| PostPersistentNotificationStore.GetSingle |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 83ms| 80ms | -3ms | -3.611
| PostPriorityStore.GetForPost |  Avg| 8ms| 7ms | -1ms | -11.904
| |  P99| 94ms| 92ms | -2ms | -2.121
| PostPriorityStore.GetForPosts |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 181ms| 171ms | -10ms | -5.512
| PostStore.AnalyticsPostCount |  Avg| 253ms| 607ms | 354ms | 140.053
| |  P99| 990ms| 2.47s | 1.48s | 149.495
| PostStore.Delete |  Avg| 40ms| 32ms | -8ms | -20.221
| |  P99| 237ms| 99ms | -138ms | -58.166
| PostStore.Get |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 225ms| 219ms | -6ms | -2.669
| PostStore.GetEtag |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 123ms| 100ms | -23ms | -18.768
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 71ms| 68ms | -3ms | -4.218
| PostStore.GetPostIdBeforeTime |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 93ms| 91ms | -2ms | -2.143
| PostStore.GetPostReminderMetadata |  Avg| 11ms| 13ms | 2ms | 18.450
| |  P99| 93ms| 209ms | 116ms | 124.065
| PostStore.GetPostReminders |  Avg| 11ms| 16ms | 5ms | 46.487
| |  P99| 209ms| 212ms | 3ms | 1.432
| PostStore.GetPosts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 80ms| 79ms | -1ms | -1.257
| PostStore.GetPostsAfter |  Avg| 11ms| 10ms | -1ms | -9.340
| |  P99| 116ms| 88ms | -28ms | -24.224
| PostStore.GetPostsBefore |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 130ms| 106ms | -24ms | -18.521
| PostStore.GetPostsByThread |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 94ms| 93ms | -1ms | -1.067
| PostStore.GetPostsSince |  Avg| 27ms| 26ms | -1ms | -3.757
| |  P99| 210ms| 205ms | -5ms | -2.386
| PostStore.GetSingle |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 93ms| 89ms | -4ms | -4.296
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 30ms| 29ms | -1ms | -3.350
| |  P99| 335ms| 293ms | -42ms | -12.537
| PostStore.SearchPostsForUser |  Avg| 253ms| 259ms | 6ms | 2.372
| |  P99| 2.407s| 2.405s | -2ms | -0.083
| PostStore.SetPostReminder |  Avg| 37ms| 35ms | -2ms | -5.425
| |  P99| 241ms| 395ms | 154ms | 64.033
| PostStore.Update |  Avg| 31ms| 26ms | -5ms | -16.287
| |  P99| 280ms| 231ms | -49ms | -17.499
| PreferenceStore.DeleteCategoryAndName |  Avg| 12ms| 10ms | -2ms | -16.769
| |  P99| 92ms| 48ms | -44ms | -48.087
| PreferenceStore.Get |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 105ms| 99ms | -6ms | -5.688
| PreferenceStore.GetAll |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 93ms| 90ms | -3ms | -3.211
| PreferenceStore.Save |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 227ms| 226ms | -1ms | -0.440
| ProductNoticesStore.ClearOldNotices |  Avg| 41ms| 36ms | -5ms | -12.218
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 32ms| 2ms | -30ms | -94.108
| |  P99| 99ms| 5ms | -94ms | -95.431
| ProductNoticesStore.View |  Avg| 57ms| 56ms | -1ms | -1.750
| |  P99| 709ms| 653ms | -56ms | -7.901
| ReactionStore.GetForPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 86ms| 88ms | 2ms | 2.321
| RetentionPolicyStore.GetAll |  Avg| 2ms| 20ms | 18ms | 1066.755
| |  P99| 5ms| 50ms | 45ms | 909.091
| RetentionPolicyStore.GetCount |  Avg| 4ms| 9ms | 5ms | 117.691
| |  P99| 24ms| 25ms | 1ms | 4.124
| RoleStore.ChannelHigherScopedPermissions |  Avg| 11ms| 20ms | 9ms | 85.625
| |  P99| 48ms| 96ms | 48ms | 100.743
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 0s | -2ms | -122.528
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 190ms| 187ms | -3ms | -1.582
| SessionStore.GetLRUSessions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 75ms| 73ms | -2ms | -2.683
| SessionStore.GetSessionsExpired |  Avg| 16ms| 4ms | -12ms | -76.576
| |  P99| 94ms| 24ms | -70ms | -74.074
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 86ms| 82ms | -4ms | -4.661
| SessionStore.Remove |  Avg| 14ms| 7ms | -7ms | -49.855
| |  P99| 93ms| 44ms | -49ms | -52.547
| SessionStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 143ms| 133ms | -10ms | -6.997
| SessionStore.UpdateLastActivityAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 89ms| 86ms | -3ms | -3.353
| StatusStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 69ms| 69ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 13ms| 11ms | -2ms | -15.136
| |  P99| 128ms| 119ms | -9ms | -7.059
| StatusStore.SaveOrUpdate |  Avg| 96ms| 96ms | 0s | 0.000
| |  P99| 1.398s| 990ms | -408ms | -29.191
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 14ms| 17ms | 3ms | 20.755
| |  P99| 230ms| 96ms | -134ms | -58.324
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 84ms | -5ms | -5.635
| SystemStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 80ms| 76ms | -4ms | -5.008
| SystemStore.PermanentDeleteByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SystemStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SystemStore.SaveOrUpdate |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 15ms| 8ms | -7ms | -46.532
| |  P99| 96ms| 25ms | -71ms | -73.954
| TeamStore.Get |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 86ms | -5ms | -5.497
| TeamStore.GetActiveMemberCount |  Avg| 82ms| 86ms | 4ms | 4.882
| |  P99| 244ms| 245ms | 1ms | 0.410
| TeamStore.GetAllPage |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 87ms| 85ms | -2ms | -2.302
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 86ms | -4ms | -4.425
| TeamStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 41ms | -4ms | -8.983
| TeamStore.GetTeamsByUserId |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 89ms| 85ms | -4ms | -4.480
| TeamStore.GetTeamsForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 88ms | -1ms | -1.122
| TeamStore.GetTotalMemberCount |  Avg| 78ms| 83ms | 5ms | 6.394
| |  P99| 244ms| 245ms | 1ms | 0.410
| TeamStore.SaveMember |  Avg| 40ms| 40ms | 0s | 0.000
| |  P99| 242ms| 240ms | -2ms | -0.828
| ThreadStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 116ms| 125ms | 9ms | 7.774
| ThreadStore.GetMembershipForUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 96ms| 93ms | -3ms | -3.114
| ThreadStore.GetTeamsUnreadForUser |  Avg| 12ms| 11ms | -1ms | -8.367
| |  P99| 142ms| 117ms | -25ms | -17.567
| ThreadStore.GetThreadFollowers |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 84ms | -4ms | -4.531
| ThreadStore.GetThreadForUser |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 190ms| 188ms | -2ms | -1.052
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 101ms| 97ms | -4ms | -3.962
| ThreadStore.GetThreadsForUser |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 131ms| 121ms | -10ms | -7.618
| ThreadStore.GetTotalThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 87ms | -1ms | -1.138
| ThreadStore.GetTotalUnreadMentions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 88ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 86ms | -2ms | -2.285
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 88ms | -1ms | -1.126
| ThreadStore.MaintainMembership |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 223ms| 215ms | -8ms | -3.582
| ThreadStore.MarkAllAsReadByChannels |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 98ms| 91ms | -7ms | -7.115
| ThreadStore.MarkAllAsReadByTeam |  Avg| 26ms| 3ms | -23ms | -89.996
| |  P99| 98ms| 5ms | -93ms | -94.899
| ThreadStore.MarkAsRead |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 87ms| 86ms | -1ms | -1.155
| ThreadStore.UpdateMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 86ms | -3ms | -3.387
| TokenStore.Cleanup |  Avg| 25ms| 49ms | 24ms | 94.388
| |  P99| 98ms| 99ms | 1ms | 1.020
| UserAccessTokenStore.GetByToken |  Avg| 12ms| 10ms | -2ms | -16.952
| |  P99| 139ms| 78ms | -61ms | -43.882
| UserStore.AnalyticsActiveCount |  Avg| 53ms| 44ms | -9ms | -17.127
| |  P99| 99ms| 98ms | -1ms | -1.008
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 8ms| 4ms | -4ms | -49.701
| |  P99| 49ms| 24ms | -25ms | -51.282
| UserStore.AutocompleteUsersInChannel |  Avg| 74ms| 74ms | 0s | 0.000
| |  P99| 330ms| 347ms | 17ms | 5.157
| UserStore.Count |  Avg| 39ms| 25ms | -14ms | -35.866
| |  P99| 375ms| 91ms | -284ms | -75.733
| UserStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 84ms| 83ms | -1ms | -1.197
| UserStore.GetAllProfiles |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 64ms| 55ms | -9ms | -14.042
| UserStore.GetAllProfilesInChannel |  Avg| 452ms| 434ms | -18ms | -3.979
| |  P99| 2.277s| 2.193s | -84ms | -3.689
| UserStore.GetByUsername |  Avg| 11ms| 10ms | -1ms | -9.309
| |  P99| 167ms| 96ms | -71ms | -42.540
| UserStore.GetForLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 80ms| 80ms | 0s | 0.000
| UserStore.GetMany |  Avg| 10ms| 6ms | -4ms | -40.216
| |  P99| 82ms| 44ms | -38ms | -46.340
| UserStore.GetProfileByIds |  Avg| 11ms| 10ms | -1ms | -9.421
| |  P99| 107ms| 100ms | -7ms | -6.537
| UserStore.GetProfilesByUsernames |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 114ms| 108ms | -6ms | -5.253
| UserStore.GetProfilesInChannel |  Avg| 73ms| 122ms | 49ms | 66.895
| |  P99| 463ms| 494ms | 31ms | 6.691
| UserStore.GetProfilesNotInChannel |  Avg| 10ms| 11ms | 1ms | 9.554
| |  P99| 24ms| 46ms | 22ms | 90.064
| UserStore.GetRecentlyActiveUsersForTeam |  Avg| 75ms| 86ms | 11ms | 14.685
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 87ms | -3ms | -3.341
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 40ms | 3ms | 8.088
| UserStore.Save |  Avg| 83ms| 83ms | 0s | 0.000
| |  P99| 307ms| 309ms | 2ms | 0.652
| UserStore.Search |  Avg| 53ms| 54ms | 1ms | 1.870
| |  P99| 234ms| 233ms | -1ms | -0.427
| UserStore.Update |  Avg| 22ms| 24ms | 2ms | 9.049
| |  P99| 237ms| 225ms | -12ms | -5.068
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 7ms | -1ms | -13.063
| |  P99| 85ms| 79ms | -6ms | -7.063
| UserStore.UpdateLastLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 66ms| 63ms | -3ms | -4.548
| UserStore.UpdateUpdateAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 69ms| 63ms | -6ms | -8.696
| UserTermsOfServiceStore.GetByUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 81ms| 78ms | -3ms | -3.723
| WebhookStore.GetOutgoingByTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 141ms| 147ms | 6ms | 4.248
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 458ms| 415ms | -43ms | -9.398
| | P99| 2.233s| 2.132s | -101ms | -4.524
| addTeamMember | Avg| 1.271s| 1.291s | 20ms | 1.573
| | P99| 7.222s| 6.363s | -859ms | -11.894
| autocompleteChannelsForTeamForSearch | Avg| 96ms| 84ms | -12ms | -12.505
| | P99| 249ms| 1.382s | 1.133s | 454.325
| autocompleteUsers | Avg| 64ms| 64ms | 0s | 0.000
| | P99| 265ms| 287ms | 22ms | 8.313
| channelMemberCountsByGroup | Avg| 12ms| 0s | -12ms | -100.868
| | P99| 90ms| 0s | -90ms | -100.279
| createCategoryForTeamForUser | Avg| 120ms| 69ms | -51ms | -42.632
| | P99| 492ms| 244ms | -248ms | -50.355
| createChannel | Avg| 869ms| 525ms | -344ms | -39.566
| | P99| 2.44s| 2.415s | -25ms | -1.025
| createDirectChannel | Avg| 481ms| 442ms | -39ms | -8.110
| | P99| 2.342s| 2.428s | 86ms | 3.672
| createGroupChannel | Avg| 690ms| 759ms | 69ms | 10.004
| | P99| 3.025s| 4.33s | 1.305s | 43.138
| createPost | Avg| 831ms| 807ms | -24ms | -2.887
| | P99| 4.629s| 4.375s | -254ms | -5.488
| createUser | Avg| 235ms| 236ms | 1ms | 0.425
| | P99| 1.556s| 1.527s | -29ms | -1.864
| deleteDraft | Avg| 23ms| 4ms | -19ms | -84.116
| | P99| 97ms| 5ms | -92ms | -94.359
| deletePost | Avg| 76ms| 54ms | -22ms | -29.122
| | P99| 479ms| 243ms | -236ms | -49.295
| followThreadByUser | Avg| 53ms| 44ms | -9ms | -17.128
| | P99| 455ms| 240ms | -215ms | -47.253
| getAllTeams | Avg| 9ms| 8ms | -1ms | -11.540
| | P99| 106ms| 98ms | -8ms | -7.530
| getAnalytics | Avg| 95ms| 56ms | -39ms | -41.205
| | P99| 468ms| 228ms | -240ms | -51.321
| getCategoriesForTeamForUser | Avg| 30ms| 43ms | 13ms | 43.301
| | P99| 234ms| 235ms | 1ms | 0.427
| getChannel | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 194ms| 217ms | 23ms | 11.864
| getChannelMember | Avg| 20ms| 19ms | -1ms | -5.014
| | P99| 230ms| 225ms | -5ms | -2.173
| getChannelMembers | Avg| 44ms| 21ms | -23ms | -52.202
| | P99| 242ms| 98ms | -144ms | -59.382
| getChannelMembersForTeamForUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 117ms| 101ms | -16ms | -13.646
| getChannelMembersForUser | Avg| 38ms| 13ms | -25ms | -65.512
| | P99| 236ms| 25ms | -211ms | -89.219
| getChannelStats | Avg| 6ms| 7ms | 1ms | 16.207
| | P99| 99ms| 99ms | 0s | 0.000
| getChannelUnread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 144ms| 125ms | -19ms | -13.210
| getChannelsForTeamForUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 134ms| 124ms | -10ms | -7.484
| getChannelsForUser | Avg| 12ms| 11ms | -1ms | -8.454
| | P99| 122ms| 97ms | -25ms | -20.412
| getClientConfig | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 229ms| 224ms | -5ms | -2.180
| getClientLicense | Avg| 1ms| 2ms | 1ms | 83.788
| | P99| 10ms| 24ms | 14ms | 145.832
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 63ms| 62ms | -1ms | -1.583
| | P99| 339ms| 297ms | -42ms | -12.398
| getFileThumbnail | Avg| 51ms| 50ms | -1ms | -1.949
| | P99| 251ms| 246ms | -5ms | -1.993
| getFilteredUsersStats | Avg| 82ms| 25ms | -57ms | -69.842
| | P99| 247ms| 50ms | -197ms | -79.757
| getGroups | Avg| 12ms| 4ms | -8ms | -68.002
| | P99| 49ms| 24ms | -25ms | -51.415
| getGroupsAssociatedToChannelsByTeam | Avg| 11ms| 2ms | -9ms | -80.860
| | P99| 25ms| 5ms | -20ms | -80.835
| getJobsByType | Avg| 9ms| 19ms | 10ms | 105.397
| | P99| 25ms| 96ms | 71ms | 287.448
| getLicenseSelfServeStatus | Avg| 100ms| 90ms | -10ms | -9.967
| | P99| 247ms| 247ms | 0s | 0.000
| getPoliciesCount | Avg| 18ms| 1ms | -17ms | -95.050
| | P99| 25ms| 5ms | -20ms | -80.483
| getPostThread | Avg| 56ms| 54ms | -2ms | -3.550
| | P99| 459ms| 437ms | -22ms | -4.796
| getPostsForChannel | Avg| 101ms| 95ms | -6ms | -5.943
| | P99| 981ms| 933ms | -48ms | -4.895
| getPostsForChannelAroundLastUnread | Avg| 44ms| 43ms | -1ms | -2.254
| | P99| 459ms| 443ms | -16ms | -3.485
| getPreferences | Avg| 9ms| 8ms | -1ms | -11.352
| | P99| 97ms| 93ms | -4ms | -4.135
| getPrevTrialLicense | Avg| 12ms| 5ms | -7ms | -58.293
| | P99| 48ms| 47ms | -1ms | -2.101
| getProductNotices | Avg| 33ms| 2ms | -31ms | -95.231
| | P99| 99ms| 5ms | -94ms | -95.431
| getProfileImage | Avg| 92ms| 88ms | -4ms | -4.337
| | P99| 489ms| 479ms | -10ms | -2.044
| getPublicChannelsForTeam | Avg| 32ms| 34ms | 2ms | 6.309
| | P99| 196ms| 209ms | 13ms | 6.627
| getRolesByNames | Avg| 3ms| 2ms | -1ms | -28.578
| | P99| 24ms| 10ms | -14ms | -58.455
| getSelfHostedProducts | Avg| 137ms| 0s | -137ms | -100.013
| | P99| 495ms| 0s | -495ms | -100.001
| getSystemPing | Avg| 5ms| 4ms | -1ms | -21.743
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamMember | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 130ms| 99ms | -31ms | -23.885
| getTeamMembersForUser | Avg| 10ms| 9ms | -1ms | -10.275
| | P99| 119ms| 109ms | -10ms | -8.372
| getTeamStats | Avg| 89ms| 98ms | 9ms | 10.123
| | P99| 244ms| 246ms | 2ms | 0.820
| getTeamsForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 91ms| 87ms | -4ms | -4.415
| getTeamsUnreadForUser | Avg| 15ms| 14ms | -1ms | -6.570
| | P99| 202ms| 189ms | -13ms | -6.443
| getThreadsForUser | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 154ms| 145ms | -9ms | -5.854
| getUser | Avg| 13ms| 12ms | -1ms | -7.891
| | P99| 217ms| 212ms | -5ms | -2.299
| getUserLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 29ms| 30ms | 1ms | 3.480
| getUsers | Avg| 14ms| 13ms | -1ms | -7.189
| | P99| 220ms| 220ms | 0s | 0.000
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 41ms| 40ms | -1ms | -2.454
| getUsersByNames | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 128ms| 124ms | -4ms | -3.114
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 69ms| 58ms | -11ms | -15.954
| | P99| 100ms| 100ms | 0s | 0.000
| login | Avg| 165ms| 158ms | -7ms | -4.230
| | P99| 1.44s| 1.194s | -246ms | -17.082
| logout | Avg| 161ms| 191ms | 30ms | 18.623
| | P99| 875ms| 491ms | -384ms | -43.885
| patchPost | Avg| 166ms| 151ms | -15ms | -9.037
| | P99| 1.43s| 1.21s | -220ms | -15.382
| removeUserCustomStatus | Avg| 303ms| 310ms | 7ms | 2.311
| | P99| 1.7s| 1.87s | 170ms | 10.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 37ms| 34ms | -3ms | -8.212
| | P99| 265ms| 241ms | -24ms | -9.064
| searchAllChannels | Avg| 61ms| 60ms | -1ms | -1.649
| | P99| 240ms| 239ms | -1ms | -0.417
| searchGroupChannels | Avg| 14ms| 20ms | 6ms | 41.697
| | P99| 145ms| 174ms | 29ms | 20.050
| searchPostsInTeam | Avg| 279ms| 286ms | 7ms | 2.509
| | P99| 2.467s| 2.454s | -13ms | -0.527
| searchUsers | Avg| 56ms| 56ms | 0s | 0.000
| | P99| 237ms| 236ms | -1ms | -0.422
| setPostReminder | Avg| 91ms| 85ms | -6ms | -6.594
| | P99| 476ms| 790ms | 314ms | 65.931
| unfollowThreadByUser | Avg| 57ms| 49ms | -8ms | -14.072
| | P99| 420ms| 321ms | -99ms | -23.543
| updateCategoriesForTeamForUser | Avg| 184ms| 206ms | 22ms | 11.986
| | P99| 1.705s| 1.81s | 105ms | 6.158
| updatePreferences | Avg| 35ms| 34ms | -1ms | -2.894
| | P99| 361ms| 262ms | -99ms | -27.461
| updateReadStateAllThreadsByUser | Avg| 26ms| 3ms | -23ms | -89.590
| | P99| 98ms| 5ms | -93ms | -94.899
| updateReadStateThreadByUser | Avg| 130ms| 128ms | -2ms | -1.535
| | P99| 887ms| 831ms | -56ms | -6.313
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 483ms| 466ms | -17ms | -3.522
| | P99| 2.142s| 2.092s | -50ms | -2.334
| upsertDraft | Avg| 9ms| 15ms | 6ms | 64.834
| | P99| 25ms| 49ms | 24ms | 97.166
| viewChannel | Avg| 41ms| 40ms | -1ms | -2.442
| | P99| 414ms| 393ms | -21ms | -5.069
